# Chapter 7 Forms 

`Forms` : Allow for the retrieval of information from users and also allows for the searching of information across the web. 

- Form Control 

1. `Adding Text`
  -Text Input 
  -PW Input
2. `Makking Choices`
  - Radio Buttons 
  - CheckBoxes 
3. `Submitting Choices`
  - Submit Buttons 
  - Image Buttons 

- How forms works 

    - Server takes information from user 
    - Server processes information with specific language 
    - Server creates a new page to send back to the browser on the information recieved 

- Form Structure 

  `<form>`
      `action`: URL to specific website
      `method`: 
        - get : short forms 
        - post : long information or password sensitive 
  `<input>`
      `type=text`: single input for line
      `name`
      `maxlength`: limits number of characters allowed
      `type=password`: allows for password input 
      `type=radio`: allows users to pick a specific option
      `type=checkbox`: allows for a check box 
      `type=file`: you upload a specific file
      `type=submit`: you can submit information to the server
      `type="image"`: you can use an image for the select button
      `type="date"`: allows for input of date
      `type=email`: enter for email
      `type=url`: enter for url
      `type=search`: enter for search 

  `<textarea>`
      - Gives a section for allowed text
  `<select>`
      - Creates dropdown list for selections 
      `multiple`: you can select multiple choices
  `<option>`
      - You can select an option from the list 

- HTML 5 form validation
  - ensures users are submitting a proper answer

# Chapter 14 Lists, Tables, & Forms 

- list-style-type 
    -unordered lists 
    - in css you can change the listing style with these functions 
      - `decimal`
      - `decimal leading-zero`
      - `lower-alpha`
      - `upper-alpha`
      - `lower-roman`
      - `upper-roman`

- list-style-position
    - `inside`
    - `outside`

- Boders between cells 
    - `collapse`
    -`separate`

- CSS to style forms 
  - There are many different ways to style forms using the attributes we have learbed previously 

# Chapter 6 Events 

- You can write code to trigger different actions depending on the event 
    - Interactions create events 
    - Events trigger code 
    - Code responds to user 

- Different Events 
    UI 
      -`load `
      -`unload`
      -`error `
      -`resize`
      -`scroll `
    Keyboard
      -`keydown` 
      -`keyup`
      -`keypress`
    Mouse 
      -`click`
      -`dbclick `
      -`mousedown`
      -`mouseup`
      -`mousemove`
      -`mouseover` 
      -`mouseout`
    Focus
      -`focus`
      -`blur `
    Form
      -`input`
      -`change `
      -`submit`
      -`reset`
      -`cut `
      -`copy`
      -`paste`
      -`select`
    Mutation
      -`DOMSubtreeModified` 
      -`DOMNodeInserted `
      -`DOMNodeRemoved`
      -`DOMNodeInsertedIntoDocument`
      -`DOMNodeRemovedFromDocument` 

### How events trigger code 

1. Select Element 
2. Indicate Event 
3. State Code 

### 3 Ways to bind an event to an element 

1. HTML event handlers 
2. Traditional DOM event handlers 
3. DOM Level 2 event listeners 

- `one.event`: handles with handles one at a time 

- `eventlistener`: can handle more than one event or function but is not supported by old browsers 


[Home](README.md)
