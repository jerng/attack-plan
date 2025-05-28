# attack-plan
What is the Functional Programming form of every popular computer language? Would knowing this, make it easier to build new languages?

## drunk text (attack plan)^2

1. Make a list of all programming language features of interest.
2. Map each feature to >=1  functional programming forms, if possible.
3. Build a compilation graph that shows how to implement any feature from (2.) to C ( or some sort of abstract syntax tree ).
4. Declare spurious victory.
5. Show how various popular languages can be approximately modeled in (2.) and implemented via (3.)

## 2025-05-28 note

Clutter. In language-design. Let's talk JUST about computer programming languages. ( Let's NOT talk about how many ways there are to say the same thing in regular languages like English. ( What's "formal English" to one person, is just "some informal natural language" to another. ) )

>   1. Too many ways to write a loop. There should be only one.
>   2. Too many ways to address a dictionary/ map. TSBOO
>   3. Too many ways to define a block/ function/ subroutine/ scope. ( All "objects" in OOP, are mere managed scopes. ) TSBOO
>   4. Too many ways to address blocks ( et tu, "modules" ) and to mark dependencies upon each other. FORTUNATELY this is usually terse, but perhaps it could be improved further. 
>   5. Too many ways for blocks to interop. FORTUNATELY the pattern of errors as values is getting more popular.
>   6. There are four kinds of brackety-looking-things in ASCII. Maybe they should all mean the same thing.
>   7. Maybe compilers should have some sort of DRY/tsboo error code.
>   8. And because there are so many languages as a result, we don't have a single SIRII ... a standard intermediate representation for information interchange. ( XKCD#927 )

But if we had only one, then all language designers could just target that, for academic purposes, while still doing whatever else they wanted outside of academia.
