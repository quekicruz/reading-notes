# JavaScript Call Stack 

- `Call`
    - Function invocation and it is what the call stack is used for 

- The `call stack` is a single, function exection and it is done one at a time from top to bottom, that means the call stack is `synchronous`

- `LIFO` 
  - Last In, First Out 
  - It is in reference to the call stack which is a data strcuture to temporarily store and manage function invocations 
  - It also means that the last function that gets pushed is the first to be popped out when the function returns 

- Call Stack EX: 
  function firstFunction(){
  console.log("Hello from firstFunction");
 }

 - function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
 }

 - secondFunction();

 * [This](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/) link will bring you where I got my example from.

- `Stack Overflow` 
  - occurs when a recursive function has no exit point 


# JavaScript Error Messages 

- `Reference Error` 
    - It is when a variable is trying to be used without declaration 
    - Also occurs when using `const` and `let` like a function keyword without proper hoisting


- `Syntax Errors` 
    - It is when something can not be parsed in terms of syntax. 
    - Can be fixed by fixing syntax 

- `Range Errors` 
    - When trying to manipulate an object with some kind of length and invalid length is given 

- `Type Errors` 
  - Occurs when the types you are trying to use or access or are incompatible
  - The most frequent error in JS 
  - 

- `Breakpoint` 
  - It is an intentional stop in code used for debugging code 


- The word `debugger` itself allows for the breakpoint to occur and helps developers see how code runs during execution


## Things I want to know more about 

- I want to practice debugging more and adding more breakpoints when I actually run my code to find bugs. 

- I also want to keep understanding the new concepts in a larger depth to improve my skills as a developer. 



* [Home](Code301Notes.md)