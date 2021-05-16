# Functional Programming 

- `Functional Programming`
  - programming paradigm- a style of building the structure and elements of computer programs- that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

- `Pure Functions` 
  - Test of purity:
    - It returns the same result if given the same arguments (also called `deterministic`)
    - Does not have any observable side effects 

- `Pure Functions Benefits` 
  - The code is easier to test

- `Immutability` 
  - In code, the state cannot change after its created. 
  - You can't change an immutable object. 
  - You create a new object with a new value instead

- `Referential Transparency` 
  - If a function consistently yields the same results for the same input
  - EX: 
    - `pure functions + immutable data = referential transparency`



# Modules & Require()

- `Module` 
    - Different bit of code that offers a specific type of functionality 

- `Require` 
    - It allows for a function to be called elsewhere and becomes a gloabl scope 


- The way we bring another module into the file we are working in is with this property:
    - `module.exports = name of function`
    - You will also have to create a variable for the require function to callback the specific function you have exporting out of the module to make it avaiable. 



## Things I want to know more about 

- I want to actually try the require() function as well as the module export property. 



* [Home](Code301Notes.md)