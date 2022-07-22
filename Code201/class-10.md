# Code 201 - Reading 10

## Troubleshooting JavaScript

1. Name some key differences between a Syntax Error and a Logic Error.

    A syntax error is caught by the interpreter or the just-in-time compiler and will log an error to the console regarding the error. It complains, with a specific line of code that seems to be causing the problem, and it terminates the process.  A logical error has none of these behaviors.  The code runs correctly, but the behavior is not as expected to the programmer, so the bug is a logical error, and the interpreter / compiler cannot help to locate this error.
  
2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

    I remember inspecting the html structure in the browser and checking the console for error messages. Once, when my CSS styling of a table produced unexpected results, a jagged table with colomns not aligning correctly, the logical error was found by an inspection that showed the table structure was off, and the solution was to correct the JS code that appended to this table.  

3. How will this topic continue to influence your long term goals?

    Code is about implenting big ideas with nitty gritty logic, and to make it work, there's often a need to find and fix (and prevent) logical errors.  Good naming conventions, concise code, and regular testing, can go a long way toward addressing errors.

## JavaScript Debugger

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

    The debugger can pause execution at a certain point (a break point), allow the programmer to see all values at that point, and then step forward, line by line (or actually, per statement), to update all values, continuing execution in slow motion, allowing the programmer to see what is happening, and hopefully, to understand how to solve any logical errors.

2. Define what a breakpoint is.

    A breakpoint is where the debugger should pause the execution of the program and await orders, usually either to step forward in code or to end program after the programmer has seen the values at that point in the script's execution.

3. What is the call stack?

    It's all the functions being called, ordered in a stack, so the first in is the last out, allowing the most recent calls to be processed first.  For example, if runProgram() is the first function, this function won't close (and destroy all resources within), until all the functions inside, higher on the stack, have run.

## Things I Want to Know More About

  I'm looking forward to learning about the VS Code debugger for JS. Understanding the differenc between stack memory and the heap is also something I've been learning about for some time and still would like to grasp better.

[Back to Home](../index.md)