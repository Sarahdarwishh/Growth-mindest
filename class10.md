# Error Handling & Debugging.

java Script EXECUTION CONTEXTS :

 1. GLOBAL CONTEXT: he code in the whole script not inside functions .
 2. FUNCTION CONTEXT:the code inside function called function context.
 3.  EVAL CONTEXT (NOT SHOWN): Text is executed like code in an internal function.


# 
 
 VARIABLE SCOPE:

 1. GLOBAL SCOPE:is declared outside a function.
 2. FUNCTION-LEVEL SCOPE: is declared within a function.

 #
 

**There is a several way to discover errors in your code in javascript :**

1. THE CONSOLE & DEV TOOLS Tools .
2. How code can deal with potential errors gracefully there are ways to expect errors and handle them without the enite code beaking and not working 
3. COMMON PROBLEMS Common sources of errors, and how to solve them.

# 

**There are three common types  of errors in Javascript**
1. SyntaxError:error in writing the syntax of the code
2. ReferenceError: when try to referance to non exist variable.
3. TypeError: when the value is not in expected data type.

#



***Debugging:*** is the process of finding and resolving bugs (defects or problems that prevent correct operation) within computer programs, software, or systems.

# 


**Debugging process:**

1. Reproduce the problem.

2. Describe the bug. Try to get as much input from the user to get the exact reason.

3. Capture the program snapshot when the bug appears. Try to get all the variable values and states of the program at that time.

4. Analyse the snapshot based on the state and action. Based on that try to find the cause of the bug.

5. Fix the existing bug, but also check that any new bug does not occur.

# 

**Try to Catch:**
- try: to specify the code that might throw an exception.
- catch: catches the exception if occured in the try.
- throw : lets you create custom errors.
- finally: will run either way (passed or failed).


