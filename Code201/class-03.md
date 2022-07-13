# Code201 - Reading 3

## HTML

### Ordered and Unordered Lists

1. When should you use an unordered list in your HTML document?

    Use an unorderd list when a list doesn't have a logical order, like for a list of ingredients.

2. How do you change the bullet style of unordered list items?

    The HTML type tag can set the bullet style to "circle", "disc", or "square", however, we may also use CSS to style bullets, for exampls:

    ```css
    ul.a {
    list-style-type: square;
    }
    ```

3. When should you use an ordered list vs an unorder list in your HTML document?

    When a list doesn't have a logical order, like for a list of ingredients, use an unordered list.  When a list has a logical order, like in steps to complete a recipe, use an ordered list.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

    The \<ol> element accepts tags such as reversed, start, type, however, we can may prefer to use CSS, such as the following:

    ```css
    ol.a {
    list-style-type: lower-alpha;
    }
    ```

## CSS

### The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

2. List and describe the four parts of an HTML elements box as referred to by the box model.

## JS

### Arrays, Operators, Expressions, Conditionals, Loops

1. What data types can you store inside of an Array?

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

    ```js
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]]; 
    ```

    Yes, the array above is valid JavaScript for a multidimensional array, which in JS is a "list-like object" rather than a C-style array, so it can store multiple types, is dynamically sized, and has a number of built-in functions.  To access the values, we can use the array's functions or a syntax like:

    ```js
    people[0][0];  // Returns "pete"
    ```

3. List five shorthand operators for assignment in javascript and describe what they do.

    These are probably the most common:

    ```text
    Addition Assignment:
    x += f() means x = x + Expression 
    
    Subtraction Assignment:
    x -= f() means x = x - Expression 
    
    Multiplication Assignment:
    x *= f() means x = x * Expression

    Division Assignment:
    x /= f() means x = x / Expression

    Modulo Assignment:
    x %= f() means x = x % Expression
    ```

    The first four should be self-explanatory by the chart, the last, modulo, is a bit less known to nonprogrammers, and it assigns the remainder of x divided by y, useful for many tasks, such as finding even or odd numbers, or every "z" number.

    JS has many more shorthand operators - all good to learn.

4. Read the code below and evaluate the last expression and explain what the result would be and why.

    ```js
     let a = 10;
     let b = 'dog';
     let c = false;

    // Evaluate this
     (a + c) + b;
   ```

   The result is "10dog". The expression in parenthesis is evaluated first, which is coersed into (10 + 0) since false converts to zero, and this equals 10. Then, 10 is concatonated with the string.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

    A conditional statement should be used when there's a boolean condition, as in the following:

    ```js
    let sleepy = true;
    if (sleepy){
      sleep();
    }
    ```

6. Give an example of when a Loop is useful in JavaScript.

    I used a for loop in our lab today so that I would not have to repeate numberous related statements.  In general, I believe a for loop may have less memory overhead than recursive function calls, but it may be more intensive on the processor.  Functions can be more semantic, since they usually have meaningful names, unlike a loop, but loops allow inline iteration.  Both are very useful tools.

## Things I Want To Know More About

The list of shorthand operators was impressive. For those that I'm not familiar, I imagine these might make code harder to read, but in general, it's good to know shorthand, so I'll be happy to study more. For example, the "Logical nullish assignment" was unknown to me, so I'll have to read more about this.  For example:

```js
let x ??= f();  // Not sure what this does yet.
```

[Back to Home](../index.md)
