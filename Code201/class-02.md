# Code 201 - Reading 2

## Introduction to HTML

1. Why is it important to use semantic elements in our HTML?

   Semantic elements allow code organzition and styling that is human friendly, unlike generic "div" or "span" elements, a semantic element has a meaning that allows a human reader to better understand and maintain the code.  

2. How many levels of headings are there in HTML?

    There are 6 levels of headings from \<h1> to \<h6>.

3. What are some uses for the \<sup> and \<sub> elements?

    They are useful for printing math and language expressions where a superscript or subscript is customary or required, like in math expression, for exponents, or like in the English language ordinal words, as in "1'st place," or in footnotes or chemical formulas.

4. When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?

    To expand the term of an \<abbr> element, add a title tag, as in:  
    \<abbr title="MyTitle">MyAbbreviation\</abbr>

## Intro to CSS

1. What are ways we can apply CSS to our HTML?

2. Why should we avoid using inline styles?

3. Review the block of code below and answer the following questions:

```css
h2 {
      color: black;
      padding: 5px;
}
```

- What is representing the selector?  
    The "h2" is the selector.

- Which components are the CSS declarations?  
    All components within curly braces are parts of a declaration.

- Which components are considered properties?

  A property is a name before a colon and value.  In the code above "color" and "padding" are properties.

## Intro to JS

1. What data type is a sequence of text enclosed in single quote marks?
2. List 4 types of JavaScript operators.
3. Describe a real world Problem you could solve with a Function.

## JS Conditionals

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.

    Condition, True

2. What is the use of an else if?

    It's an if statement that will only be executed when the preceding check fails, which is a logical shortcut. Otherwise, the same check would require a logical "and" to check the above condition plus another condition.  

3. List 3 different types of comparison operators.

    ```text
    ==, ===, < 
    ```

4. What is the difference between logical && and ||?

    These operators are for evaluating any boolean expression that has multiple sub-expressions:

    ```text
    && : True if both sides are true 
    || : True if either side is true
    ```

## Things I Want To Know More About

I'm curious on the common usage of "===" (versus "==") since I don't have much experience using this rather unique comparison operator. I imagine it's useful when concerns for type safety are strong, but I also wonder about performance and compatibility considerations. I have seen already that certain types, like null, can only be checked for specifically using the "===" operator. More on this would be good to know, so I'll look into it soon.

[Back to Home](../index.md)
