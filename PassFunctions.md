# Lists & Keys 

- `map()` - used to take an array of numbers and double it 
    - It can also be used to return numbers as an `<li>`
    - Ex: `const listItems = numbers.map((number) => <l1> {number}<li>`
    - Then you put the entire li list in a `<ul>`

- `key` : special string attribute you need to included when creating lists of elements
    - Assist React identify which items have changed, been added, or removed. 
    - You can use IDs or indexes for keys 
    - Need to unique with siblings 
    - Can be used in different arrays

# Spread Operator 

- `Spread Operator`: useful syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function's arguments. 
  - It is unique because of an ellipsis of three dots `(...)`
  - It can **spread** arguments in an array

- `...` Tasks 
  - Copying an array 
  - Concatenating or combining array 
  - Using math functions 
  - Using an array as arguments 
  - Adding an item to a list 
  - Adding to state in React 
  - Combining objects 
  - Converting NodeList to an array 

- Any function that takes in multiple functions can benefit from `...` because it can "spread" the array into different arguments 

- **EX of spread to merge Arrays**
`const cars = ['🚗', '🚙'];`
`const trucks = ['🚚', '🚛'];`
`Spread`
`const combined2 = [...cars, ...trucks];`
 `[ '🚗', '🚙', '🚚', '🚛' ]`
 
 - [This](https://www.samanthaming.com/tidbits/49-2-ways-to-merge-arrays/) link is where I got my example.

 - **EX of spread to add item to Array**
`const ocean = ['🐙', '🦀'];`
`const aquarium = [...ocean, '🐡']; // Add a single` `value`
`const sushi = [...ocean, '🐡', '🍚']; // Add multiple values`
`aquarium; // ['🐙', '🦀', '🐡']`
`sushi; //  ['🐙', '🦀', '🐡', '🍚']` 
`ocean; // ['🐙', '🦀']`

- [This](https://www.samanthaming.com/tidbits/87-5-ways-to-append-item-to-array/) link is where I got my example.

- **EX of merging objects into one.** 
- Input:

- let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
  };


- let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
  };

- let employee = {
    ...person,
    ...job
  };

- Output:

- {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356',
    jobTitle: 'JavaScript Developer',
    location: 'USA'
  }

- [This](https://www.javascripttutorial.net/object/javascript-merge-objects/) link is where I got my example. 

- The `spread operator` may not work in older browsers so : `function.prototype.apply()` will have the same effect as the `spread operator`

- It also note worthy to know if an array is deeply nested it will only take the first level of that array. 

# Pass functions between Components

- We want to use functions to change the state of whichever one you are targeting. 

- `increment` is the method used to change the state which allow for re rendering when the count is updated. 

- You can pass a method into the render component of your page `(parent)`

- The you can call that method in the parent `(child to parent)`

- 



