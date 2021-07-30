# Error Handling & Debuggin

JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

* When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it. too.
*  When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it. In this chapter you will learn about:

### THE CONSOLE & DEV TOOLS
Tools built into the browser that help you hunt for errors.
### COMMON PROBLEMS
Common sources of errors, and how to solve them.
### HANDLING ERRORS
How code can deal with potential errors gra cefully.

### ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:

![](https://th.bing.com/th/id/R.5f12c7d37753294c61bf18f17ae19817?rik=IpnKLuH19Un0Iw&pid=ImgRaw)

## EXECUT.ION CONTEXTS

* The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

#### EXECUTION CONTEXT
 Every statement in a script lives in one of three execution contexts:
 1- GLOBAL CONTEXT
 Code that is in the script, but not in a function. There is only one global context in any page.
 2- FUNCTION CONTEXT
 Code that is being run within a function. Each function has its own function context.
 3- EVAL CONTEXT (NOT SHOWN)
 Text is executed like code in an internal function called eva l {) (which is not covered in this book).
 
 #### VARIABLE SCOPE
 1- GLOBAL SCOPE
 If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.
 
 2- FUNCTION-LEVEL SCOPE
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

## UNDERSTANDING SCOPE
In the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.


## UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

#### If you are anticipating that something in your code may cause an error, you can use a set of statements to handle the error (you meet them on p480). This is important because if the error is not handled, the script will just stop processing and the user will not know why. So exception-handling code should inform users when there is a problem.

#### Whenever the interpreter comes across an error, it will look for error-handling code. In the diagram below, the code has the same structure as the code you saw in the diagrams at the start of the chapter. The statement at step 1 uses the function in step 2, which in turn uses the function in step 3. Imagine that there has been an error at step 3.

## ERROR OBJECTS
Error objects can help you find where your mistakes are and browsers have tools to help you read them.
![](https://th.bing.com/th/id/R.fb2232de8e7d1cc562280bde8b3d02dd?rik=fDKLU8fDq1xj%2bQ&pid=ImgRaw)
