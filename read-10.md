# The Call Stack defined on MDN
  - *call stack* is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function
# Understanding the JavaScript Call Stack

  - *LIFO:*Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
  - **Manage function invocation (call):** The call stack maintains a record of the position of each stack frame. 
  - A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. 
  -  The `callMyself()` will run until the browser throws a “Maximum call size exceeded”. And that is a stack overflow.

  - **The key takeaways from the call stack are:** 
    - 1. It is single-threaded. Meaning it can only do one thing at a time.
    - 2. Code execution is synchronous.
    - 3. A function invocation creates a stack frame that occupies a temporary memory.
    - 4. It works as a LIFO — Last In, First Out data structure.


# JavaScript error messages
  - **Types of error messages:**
    - *Reference errors*
       - when you try to use a variable that is not yet declared you get this type os errors
    - *Syntax errors*
       - occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
    - *Range errors*
      - Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
    - *Type errors*
      -  this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
 - **Debugging**
    - the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools.
     