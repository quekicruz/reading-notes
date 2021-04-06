# Chapter 3 Lists

### There are 3 different types of lists 

1. Ordered lists 

  - Lists is numbered 
  -  Ordered lists are created with :`<ol>`
  - Items in ordered lists have the tag: `<li>`
2. Unordered lists 

  - Lists begin with bullet points 
  - Unordered lists are created with : `<ul>`
  - Items in unordered lists have the tag: `<li>`
3. Definition lists 

  - Terms with definitions 
  - Definition lists are created with: `<dl>`
  - `<dt>` is used to for the term 
  - `<dd>` is used for the actual definition for the term 

### Nested Lists 

- There is also nested lists which are lists within lists. 


# Chapter 13 Boxes

### Box Dimensions 

  * `width`
  * `height`

  - A way to specify box dimesnions is achieved through pixels, percentages, and ems

### Limiting Width

  * `min-width`
  * `max-width`

### Limiting Height 

  * `min-height`
  * `max-height`

### Overflowing content

  * `overflow`: tells the browser what to do if content in the box is too large
  * `hidden`: hides extra content
  * `scroll`: adds a scrollbar to look at extra content

### Border,Margin, & Padding 

1. `Border`: Separates boxes from one another
2. `Margin`: Sits outside the edge of the box, can create space between boxes 
3. `Padding`: Increases the readability of content on screen

### Border Width (Percentages can not be used for this aspect)

- There are different ways to affect border width: 
    - `thin`
    - `medium`
    - `thick`

- You can also affect the sizing of borders
    - `border-top-width`
    - `border-right-width`
    - `border-bottom-width`
    - `border-left-width`

### Border Style 

- There are different border styles 

  1. `solid`: Creates solid line
  2. `dotted`: creates dotted line 
  3. `dashed`: creates dashed lines 
  4. `double`: two solid lines 
  5. `groove`: carved line page
  6. `ridge`: sticks out from page
  7. `inset`: embedded in page 
  8. `outset`: coming out of page 
  9. `hidden`: no border

### Border Color 

  - `border-color`: gives color to border

### Change inline/block

- `inline`: makes block level element in line
- `block`: makes in line element in block
- `in-line block`: makes block level element to flow like a in line element


### Hiding boxes 

- `hidden`: hides element

- `visible`: shows element

# Chapter 2 Arrays 

- `Index`: number given to items in arrays

- It is important to note that different items in arrays should have names so that they can have easier accessibility. 

- `length`: Holds the number of items in array. 

# Chapter 4 Statements 


### If else statement

- `if else statement`: True/false statment where specific code will run if statement is either true or false 
    Ex: `if(score >=50){congratulate();}else{encourage()}`

1. One set is for the `true` statement 
2. One set for the `false` statement

### Switch Statements 

- `switch statement`: starts with a `switch` variable and creates different ouputs for answer

### If else vs Switch 

- `Switch` runs a bit more efficently than an `if` statement because it can keep running

### Type Coercion & Weak Typing 

- `Type coercion`: converts data behind the scenes to complete an operation 

- `Weak typing`: data type can change quickly in javaScript 

### Truthy & Falsy 

- `Falsy`: treated as if *false*

- `Truth`: treated as if *true*

### 3 Different Loops 

1. `for`: runs loop for a specific number of times

2. `while`: runs loops without a specific number of times until truth is met

3. `do while`: will always run loop even if statement is false

- A `for` loop uses a counter as condition

  - Intialization: Create variable and set to 0
    `var i= 0`
  - Condition: Loop runs until specific number is met  
    `i < 10`
  - Update: Everytime loop runs, counter is made
    `i++`

### 3 Key Loop Concepts 

1. Keywords 

  - `break`: causes termination of the loop
  - `continue`: tells interperator to stop current loop and then run new iteration

2. Loops&Arrays 
  - Both work hand in hand to make sure loop runs properly

3. Performance Issues
  - `infinite loop`: if condition never returns false and will break your code


[Home](README.md)