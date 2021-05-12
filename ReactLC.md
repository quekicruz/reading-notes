# React: Component Lifecycle Events 

- `Lifecycle Events`: Methods used on components in React. 

- *3 Phases of Component Lifecycle*
    - `Mounting` 
      - Instance of when component is created and inserted into the DOM
    - `Updating` 
      - When component is updated
    - `Unmounting` 
      - When component is being removed from the DOM. 

- `constructor()` 
  - React component before it is mounted 

- `render()`
  - Required method in component 

- `ComponentDidMount()`
  - Method invoked immediately after a component is mounted 

- `ComponentWillUnmount()`
  - Allows for the clean up of the DOM 

- `

### Unsafe LifeCycle Events 

- `Unsafe` 
  - this keyword is no longer since it causes bugs in the program. 


# React State vs Props

- `React State`
    - They are within the component
    - If you change the state, it will re render that portion of the application
    - Can be easily updated and needs to be re render due to user interaction
    - Useful inside form 
    - 
    

- `Props` 
    - When you want to pass arguments in React and it must be rendered 
    - Also used when you want a counter in your components 
    - It can hold a bunch of different components
      - Like the title and 
    - They are outside the component \
    - You can't change them like states
    - It is a variable to a function 


## Things I want to know more about 

- I want to know HOW to use them and write them out in code 

- I also want to better understand the concepts as a whole 


* [Home](Code301Notes.md)