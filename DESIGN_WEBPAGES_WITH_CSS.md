## DESIGNING WEBPAGES WITH CSS
Cascading Style Sheets(CSS) tells the browser How the content should look. It gives sites thier desgin and layout. 

## How CSS work. 

- HTML elements have invisible boxes around them and CSS allows you to control the way that each individual box is persented. 
- CSS ssociated style rules with HTML Elements. 
    
    `p {
        font-family: lora;
        color: black;
        }`
  
  In this case lora is the font and the color of the text will be black. 
  
  - There are many different types of CSS selector that allow you to target rules to specific elements. 
  
|  Selector   |     Meaning         |  Eaxample   |
|  ----------- | ------------------- | -------------
|  Universal | Selects all elements. | * {}  |
|  Type  | Matches all elements that have the given node name. | h1, h2, h3  |
|  Class | Matches all elements that have the given class attribute. | .note {} or p.note {}  |
|  ID  | Matches an element whose class attributed has a value taht matches its Id attribute that comes after a hashtag.  | # toc |
|  Child| Matches an element that are children or comes below the parent element. | li>a {}  |
|  Descendant  | matches an element taht us a decendant(not only the child of an element). | p a {} |
|  Ajacent Sibling  | refers to an element that is the next sibling of another. | h1+p {}  |
|  General Sibling  | Similar to Ajacent Sibling but the element doesn't have to be directly perceding element.| h1~p {} |
  
## Color 

- There ways you can add color by using RBG value, Hex codes, and color names. 
- You can use color pickers to chose a color you want. 
- It is important to have enough contrast between any text and background color. 
