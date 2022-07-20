# Code 201 - Reading 8

## MDN - CSS - Flexbox

1. Flexbox is designed for one-dimensional content. Explain what this means.

    MDN wasn't very clear what was meant by flexbox being designed for "one-dimensional" content. It says, "It excels at taking a bunch of items which have different sizes, and returning the best layout for those items."  It then shows how flexbox can help create responsive content, as in shrinking an element's width to a point, then stacking. I guess one-dimension may refer to a single line of content display priorities that is maintained in relation to space available.

2. Explain the difference between the main axis and cross axis.

    The main axis follows a "flex-direction" that can be verticle or horizontal, and whichever it is, the Cross axis is the other direction.  Still digging into what this means in practical terms.

3. How can using certain properties of flexbox negatively impact accessibility?

    Changing the flow of items via CSS from the order in the HTML document could confuse screen readers as to the correct order, specifically, when using the row-reverse and the column-verse property values.

    Tabbing may also seem reversed, so user beware.

## MDN - Layout - Flexbox

1. What are some advantages of using flexbox over float?

    A flexbox has properties that allow it be repsonsive, whereas a float element may need to hard-code a responsive solution via media queries.

2. How does this topic connect with your long term goals?

    Flexbox is a tool to fit content into a page responsively, although I don't find it intuitive enough to use well out of the box, maybe it will grow on me.
  
## Things I Want to Know More About

  I'd like to see more examples of a flexbox in action for common, practical situations.  MDN began talking about special cases of accessibility and non-English design layouts rather quickly, before I had time to really absorb how a flexbox is useful in my most likely immediate use-cases, but I expect to see more examples and get a more intuitive understanding of this topic soon.  The ability to make responsive design, even without media queries, is a good topic to study.

[Back to Home](../index.md)
