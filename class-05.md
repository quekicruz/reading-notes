# Chapter 5 Images 

`stock images`: Images programmers can pay for when not personal photos. 

**It is important to create a folder for your images to be organized** 

### Adding Images 

- `<img>`: Tag needed to add image followed by `</img>`
    - `src`: attribute for source of image 
    - `alt`: describes the content of image
    - `title`: title of the image
  

### Recommended Areas for adding images in code 

1. Before paragraph 
2. Inside the start of a parapgraph 
3. In the middle of a paragraph 

### 3 Rules for creating images 

1. Save Images in the right format 
2. Save images at the right size 
3. Measure images in pixels 

### 2 Different Image Formats 

1. `JPEG`
2. `GIF`/ `PNG`

# Chapter 11 Color 

**Color brings life to your webpage!**

`color`: property that allows for color on the webpage
    - `RGB values`
    - `Hex Codes`
    - `Color names`
    - `Hue`
    - `Saturation`
    - `Brightness`

`background-color`: gives color to background of specific aspect of page

**Every color is created by using a mixture of red,green, and blue.**

- `Contrast`: Key aspect which allows for readability of your page

# Chapter 12 Text 


### Typeface Termniology 
- Some Ex: 
  - `Serif`
        - Font Styles within 
          - Georgia 
          - Times 
          - Times New Roman
  - `Sans-serif`
        - Font Styles within 
          - Arial
          - Verdana
          - Helvetica
  - `Monospace`
        - Font Styles within 
          - Courier
          - Courier New

**There are different weights for text** 
  - `light`
  - `medium`
  - `bold`
  - `black`

**There are different styles for text**
  - `Normal`
  - `Italic`
  - `Oblique`

**Different stretches**
  - `Condensed`
  - `Regular`
  - `Extended`

### Units of type size 

- `Pixels`: defined as px

- `Percentages`: defined as %

- `EMS`: defined as em

### Text Transform 

- `Uppercase`
- `lowercase`
- `capitalize`

### text-decoration

- `none`
- `underline`
- `overline`
- `line-through`
- `blink`

### text-align

- `left`
- `right`
- `center`
- `justify`

### styling links 

- `:link`
- `:visisted`

### Pseudo-classes for user interaction 

- `:hover`
- `:active`
- `:focus`

### Attribute Selectors 

- Existence: `[]`
- Equalituy: `[-]`
- Space: `[~]`
- Prefix: `[^=]`
- Substring: `[*=]`
- Suffix: `[$=]` 

# Blog Post: JPEG vs PNG vs GIF

### TL;DR 

- `JPEG`: should be used for images that contain a natural scene 

- `PNG`: should be used for images that need transparency with text & objects. 

- `GIF`: should be used for images that have animation

### Compression types 

- *lossless*
    - No information lost in compression so easier to reconstruct
    - `PNG` is a lossless image
          - No data loss = higher quality as compared to JPEG
    - `GIF` is a lossless image 
          - Only used for animations

- *lossy*
    - Irreversible data loss
    - `JPEG` is a lossy image

### Transparency 

- `JPEG`: does not support transparency 

- `PNG`: supports transparency in 2 ways 
        1. Inserts alpha channel for partial transparency
        2. Supports index transparency 

- `GIF`: not suitable for images with transparent backgrounds

### Colors 

- `JPEG`: Can support 16 million different colors 

- `PNG`: 2 main modes 
        1. PNG8: supports 256 colors
        2. PNG24: supports 16 million colors 

- `GIF`: supports 256 colors 

