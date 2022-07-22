# Code 201 - Reading 9

## HTML Forms

1. Why are forms so important in web development?

    Forms are how to capture and display user input, especially from the keyboard (but also from the mouse or elsewhere), and the form element can wrap and group elements for handling via event bubbling.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

    Keep in mind user expectations, standard styling.

3. List 5 form elements and explain their importance.

    Input box (for single line), text area (for multiple lines), button (for click / press / hover events), fieldset (for limited mutliple choice bubbles), select (typically a dropdown list menu of options) - all things we need to input any kind of data.

## JS Events

1. How would you describe events to a non-technical friend?

    Events are things that happen in code that can trigger other things to happen.  They greatly help to decouple code, so that one piece of code doesn't need the details of another piece of code to operate - it just listens for the appropriate events.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

    The event type to listen for, and a callback function, which is the name of the function or object to call.

3. Describe the event object. Why is the target within the event object useful?

    The target is the lowest level element of the event that typically stores the most relevant data related to that event, such as a name, location, or value.

4 .What is the difference between event bubbling and event capturing?

    Event bubbling is the side of event handling that JS coders tend to interact with, where events bubble from the deepest nodes to parents, responding to whatever type of event has happened to the elements on screen and their objects in code, but there is another side, which programs like the operating system tend to handle invisibly, processing the raw input before passing it to the lowest element in the bubble chain.  Both sides of handling events are accessible via JS to some degree, but again, event bubbling is the typical, default way to handle events. 

[Back to Home](../index.md)