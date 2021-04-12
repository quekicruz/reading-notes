# Understanding Problem Domain 

### Common answers to the hardest thing about writing code 

- `Learning new technology`
- `Naming Things`
- `Testing your code`
- `Debugging`
- `Fixing bugs`
- `Making software maintainable`

### Learning the problem domain is the hardest part about coding

**To better understand the problem domain, here are a few tips**

1. `Figure out what the major components of the picture are`
2. `Sort the pieces by color or component`
3. `Put together all the border pieces`
4. `Put together each component of the picture from the piles your created`

**You need a picture of where you want to start**

**Programming is easy when you understand the problem domain**

- `Make the problem domain easier`
- `Get better at understanding the problem domain`

# Chapter 3 Object Literals 

`Objects`: group together a set of variables and functions to create a model of something you would see in the real world. 

`property`: tell us more about the object/ the adjective of the object

`method`: the task of the object or the function of the object 

`key`: name of within the object or set of names/values


# Document Object Model 

`DOM`: specifies how browsers should create a model for HTML and how javascript can access and update the contents of webpage while in the window 

**DOM is neither a part of the HTML or javascript** 

`DOM tree`: specifies how the browser should be structured 
- it is made up of objects 
- each object represents different part of page 
- Model of webpage

**DOM also defines methods and properties to update each object in this model**

`DOM`= `Application Programming Interface API`

`API` = let programs and scripts talk to one another 

### 4 main parts of DOM Tree

`Document node`: added to represent the entire page/starting point for all visits of the DOM tree

`Element node`: next part of the DOM tree

`Attribute node` : Part of the element 

`Text nodes`: Child of the containing element 

#### Accessing and updating DOM Tree

1. Locate the node that represents the element you want to work with

2. Use its text content, child elements, and attributes

#### Access the elements 

- Selecting individual element node 

1. `getElementById()`: Use value of elements id 
2. `querySelector`: Uses a css selector 

- Selecting multiple nodes 

1. `getElementsByClassName()`
2. `getElementsByTagName()`
3. `querySelectorAll()`

- Transversing between element nodes

1. `parentNode`
2. `previousSibling/nextSibling`
3. `firstChild/lastChild`

`elements` = `element node`
- DOM working with an element, actually working with a node that represents that element 

#### Work with those elements 

1. Access/update text nodes
2. Work with html content 
3. Access or update attribute values 

`DOM queries`: methods that find elements in the DOM tree

#### Methods/Returns 

- Return a single element node 

`getElementById`

`querySelector`

- Return one or more elements 

`getElementsByClassName`

`getElementsByTagName`

`querySelectorAll`



`NodeList` : collection of element nodes 

`live Nodelist` : script and node list updated at the same time 

`static Nodelist` : script and node list updated not at the same time 

- Get nodelist return 

`getElementsByTagName`

`getElementsByTagName`

`getElementsByClassName`

`querySelectorAll`

- Select element from Nodelist 

`item()`

`array syntax` : It is faster 

- Select elements using css selectors 

- `querySelector`

- Select elements using class attributes 

- `getElementsByClassName`

- Selects by tag name 

- `getElementsByTagName`

### Dom Manipulation 
- Adding elements 

1. `createElement`
2. `createTextNode()`
3. `appendChild()`

- Removing Elements 

1. Store the element 
2. Store the parent of that element in a variable 
3. Remove the element from its containing element 

### Cross-Site Scripting Attacks or XSS

`XSS` : can gather information through the DOM, website cookies, session tokens 

  - Attackers can access and information and do some of the following 
    - Make purchases with that account 
    - Post defamatory content 
    - Spread their malicious code further / faster

- To defend against `XSS` there must be `validation` put in place 



[Home](README.md)


