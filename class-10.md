# JavaScript

## Error handling & Decugging

***JavaScript can be hard to learn and everyone makes mistakes when writing it This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.***


JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.


* ***o find the source of an error, it helps to know how scripts are processed.The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:***

1. The greeting variable gets its value from the greetUser() function.
2. greetUser() creates the message by combining the string 'He 11 o ' with the result of getName ().
3. getName () returns the name to greetUser() .
4. This greeting variable is written to an alert box.



### EXECUTION CONTEXTS


**The JavaScript interpreter uses the concept of execution contexts. There is one global execution context plus, each function creates a new new execution context. They correspond to variable scope.**




* If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.



* Error objects can help you find where your mistakes are and browsers have tools to help you read them.


***Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.***



- You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.



* If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.

