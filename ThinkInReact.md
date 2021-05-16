# Thinking in React 

- Accoridng to Facebook and Instagram, React is the best way to build big, fast Web apps with JavaScript.

- Here is the breakdown process for React 

    - `Step 1: Break The UI Into A Component Hierarchy`
      - It is important to draw boxes around every component and sub component and give them specific names 

      - `Single Responsibility Principle`
        - That is the idea that a component should do at least one thing and it starts to do more it should be broken down into smaller components 
      - Separate your UI into components, where each component matches one piece of of your data model.

    - `Step 2: Build A Static Version in React` 
      - Build at out a version that has no interactivity to it. 
      - Use `props` to pass data through more easily 
      - It is usually easier to build top down
      - Don't forget your `render` or `return`

    - `Step 3: Identify The Minimal (but complete) Representation Of UI State` 
      - Keep your code `DRY`
      - Think about the minimal mutable state your code needs to be in or represent 
      - State are the only components that change due to user interaction 

    - `Three Questions to Ask if a component is a state`
      1. Is it passed in from a parent via props? If so, it probably isn’t state.
      2. Does it remain unchanged over time? If so, it probably isn’t state.
      3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
    * [This](https://reactjs.org/docs/thinking-in-react.html) link is where I got those questions above. 


    - `Step 4: Identify Where Your State Should Live`
      - Which components own the state 
      - Some Tips to know which components need state 
        - Think about owner components and see if they need state
        - If they don't you can make a separate component for to hold that state and have it called back in the hierarchy. 

    - `Step 5: Add Inverse Data Flow` 
      - We need to think about the data flow of react and understand that it is unidirectional 
      - We need to understand user interaction to make certain components change their state depending on interaction 
      - It is also wise to understand how callbacks can have state change.


## Things I Want To Know 

- I just want to know all about React, it seems like such a unique tool and I feel that I am only at the tip of the iceberg. 

- I also just want to think more in React and actually go through the steps myself to actually understand the process more in depth. 



* [Home](Code301Notes.md)