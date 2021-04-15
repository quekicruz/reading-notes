# Chapter Error Handling & Debugging 

- Order of execution is extremely important due to the fact that there may be functions that need to run first before others it is also important because it can tell us where we need to fix the code 

- Statement in scripts live with 3 different `execution contexts` 

  1. Global Context
    -Code in script but not a function
  2. Function Context 
    - Code being run within a function 
  3. Eval Context (Not shown)
    -  Code as an internal function 


### 2 phases of new execution 

  1. Preparation 
    - New scope created 
  2. Execution 
    - Assignment of variables 
    - Functions and code 

- `lexical scope`: are linked to the object they were defined within

- `exception`: error messages 

### Error Objects 
- Give a description as what issue or problem you came across in your code 

- Here are some different types of errors 
  - `SyntaxError`
  - `ReferenceError`
  - `EvalError`
  - `URIError`
  - `TypeError` 
  - `RangeError`

### How to deal with erros 

- Debug the script to fix errors 
- Handle errors gracefully 

- Debugging = deduction 

- You need to breakdown the script and understand where the problem is occurring in the script 

- It is important to use your developer tools 

- You can add data in the console to test code and see if it will run 

- You can have your code step over other lines to help it run more smoothly: `Stepping Over`

- You can create a breakpoint in your code using the term: `debugger`

### The try,catch,fianlly method 

- You can make sure your code is running smoothly and test it first with these terms 

- `Try` 
- `Catch` 
- `Finally`

### Creating your own errors 

- You can throw your own errors in if you know your code will break 

#### Dubugging Tips 

- `Switch to other Browser`
- `Add Numbers`
- `Strip it back` 
- `Explaining the code`
- `Search`
- `Code Playgrounds`
- `Validation tools`

### Common Errors with code 

- `Missed/extra characters` 
- `Data type issues`


[Home](README.md)