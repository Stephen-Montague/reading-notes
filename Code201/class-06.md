# Code 201 - Reading 6

## JS

### Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

    An object is meant to represent an idea or thing, so it could be empty or have many parts, like properties that describe it, ways of doing things called methods.  

2. What are some advantages to creating object literals?

    Object literal allow you to work with a group of ideas using words, for properties or methods, rather than just numbers, as with an array index. So, it can be easier to handle than many seperate variables, and more intuitive to code and read.

3. How do objects differ from arrays?

    JS objects act like a map between strings and values (which includes properties and methods), similar to a dictionary's string keys and definitions.  This differs from an array, which relies on a set order of values accessed by a number index.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

    This part is difficult to visualize without practice, but I believe the bracket notation is especially useful for some runtime dynamic changes to the object, where a new object property or method can be created via the bracket syntax.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

   The term "This" refers to the instance of the object. For an object literal, this simply refers to itself, but later, we will also use this to construct many instances of the same object type via a contructor.

## Introduction To The DOM

1. What is the DOM?

    The DOM is an object representation of the HTML document that the JS can manipulate to makes changes to the HTML.

2. Briefly describe the relationship between the DOM and JavaScript.

The DOM allows JS to change HTML, including: adding, deleting, and modifying elements, tags, values, and just about anything, for a more interactive experience.  The direction of influence is mostly in one direction - JS operates on the HTML, rather than the reverse.

## Things I Want to Know More About

I want to learn more about JS object contruction, inheritance and composition, common design patterns for using these, and any dangers to be aware of. Soon, I also expect we'll dig into event listeners more, which will be very useful for interacting with users.

[Back to Home](../index.md)
