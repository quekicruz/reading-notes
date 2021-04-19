# Article Chart.js 

- Charts are a better tool when displaying data instead of tables 

- `Chart.js`: is a plugin with HTML5 to draw a graph on the page. 

- Different charts can be made 
    - `line chart` 
    - `pie chart` 
    -  `bar chart` 

# Download chart.js 

- It is very simple to install chart.js and it also very quick.

# <canvas> element 

- `<canvas>` : only has 2 elements which width and height 

- You need a closing tag for the tag 

- You can create 2D work using canvas element 

# Shapes with <canvas>

- It only supports 2 shapes which are `rectangle` and `paths` 

- Different shape commands 

  - `fillRect(x,y,width,height)`: draws a filled rectangle 
  - `strokeRect(x,y,width,height)`: draws a rectangle outline 
  - `clearRect(x,y,width,height)`: makes the area transparent 

- You use the `draw` function to create those rectangles 


- Drawing a path is a bit different 

    - `beginPath`: This creates a new path 
    - `closePath`: Adds a straight line to a path 
    -`stroke`: draws the outline of the shape 
    -`fill`: draws a solid shape for path content 

- With these paths you can create a variety of different shapes with combinations of diffferent elements 

# Color

- `fillStyle = color`: Sets the style used when filling shapes 

- `strokeStyle = color`: Sets color for outline of shapes 

- You can also play with the transparency of the page 

- There are also differnt line styles 
    - `lineWidth = value`: sets width of the lines 
    - `lineCap = type`: sets appearance at the end of lines 
    - `lineJoin = type`: sets appearance at the corners of lines 
    - `miterLimit = value`: establishes limit at miter 
    - `getLineDash()`: returns the current line dash pattern
    - `setLineDash(segments)`: sets the current line dash pattern 

- There are also shadows that can be created 
    - `shadowOffsetX = float`
    - `shadowOffsetY = float`
    - `shadowBlur = float` 
    - `shadowColor = color`

# Text 

- 2 methods to render text for a page 
  - `fillText(text,x,y,maxWidth])`
  - `strokeText`

- Here are some ways to style text 
  -  `font = value` 
  - `textAlign = value` 
  - `textBaseline = value` 
  - `direction = value` 


[Home](README.md)