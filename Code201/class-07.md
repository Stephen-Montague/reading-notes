# Code 201 - Reading 7

## Domain Modeling

1. Explain why we need domain modeling.

## HTML Table Basics

1. Why should tables not be used for page layouts?
    Tables are bad for screen reader accessibility, tables can require more complicated code to create & maintain, and tables aren't as responsive as CSS, in part since they automatically size to contents.

2. List and describe 3 different semantic HTML elements used in an HTML \<table>.

   \<table> denotes a table element, and \<tr> means "table row" while \<th> stands for a table header element and \<td> stands for table data - not sure if these are all really semantic, as in easily understood by human readers, but they're important parts of a table.

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?

    Constructor are functions that run to create an object and optionally to initialize its members. Constructors make objects much easier to create dynamically than  template literals.

2. How does the term this differ when used in an object literal versus when used in a constructor?

    In an object literal, "this" refers to the a specific object, whereas in a contructor, it refers to an instance of the object being created.

## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.

  In Unreal development, a game character is a kind of pawn that is a kind of actor that is a kind of object - this is an inheritance relationship. A character has all of the properties and methods of a pawn or actor, but an actor does not have all the properties and methods of a character, since one conversion is widening and the other is narrowing.

## Things I Want to Know More About

  There's much to learn about every topic, but I would like to learn more on standard frameworks and common coding practice, to be better at communicating with fellow developers and more efficient overall.

[Back to Home](../index.md)
