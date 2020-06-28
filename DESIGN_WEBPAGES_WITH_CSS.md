## DESIGNING WEB PAGES WITH CSS
Cascading Style Sheets(CSS) tells the browser How the content should look. It gives sites its design and layout. 

## How CSS work. 

- HTML elements have invisible boxes around them and CSS allows you to control the way that each individual box is presented. 
- CSS ssociated style rules with HTML Elements. 
    
    `p {
        font-family: lora;
        color: black;
        }`
  
  In this case, Lora is the font and the color of the text will be black. 
  
  - There are many different types of CSS selectors that allow you to target rules for specific elements. 
  
|  Selector   |     Meaning         |  Example   |
|  ----------- | ------------------- | -------------
|  Universal | Selects all elements. | * {}  |
|  Type  | Matches all elements that have the given node name. | h1, h2, h3  |
|  Class | Matches all elements that have the given class attribute. | .note {} or p.note {}  |
|  ID  | Matches an element whose class attributed has a value that matches its Id attribute that comes after a hashtag.  | # toc |
|  Child| Matches an element that are children or comes below the parent element. | li>a {}  |
|  Descendant  | matches an element that is a descendant(not only the child of an element). | p a {} |
|  Adjacent Sibling  | refers to an element that is the next sibling of another. | h1+p {}  |
|  General Sibling  | Similar to Adjacent Sibling selecttor but the element doesn't have to be directly preceding element.| h1~p {} |
  
## Color 

- There ways you can add color by using RBG value, Hex codes, and color names. 
- You can use color pickers to chose a color you want. 
- It is important to have enough contrast between any text and background color. 


### Site Navigation
- [Home](/README.md)
- [Growth Mindset](/GrowthMindset.md)
- [Read and Discussion](/Discussion.md)
- [Coder's Computer](/Coder'sComputer.md) 
- [Stretch Goal Class 03](/StretchGoalClass03.md)
- [Revisons and the Cloud](/Revisions_And_The_Cloud.md)
- [Structure_Webpages_With_HTML](/STRUCTURE_WEBPAGES_WITH_HTML.md)
- [Designing Webpages with CSS](/DESIGN_WEBPAGES_WITH_CSS.md)
- [DYNAMIC WEBPAGES WITH JAVASCRIPT](/DYNAMIC_WEBPAGES_WITH_JAVASCRIPT.md)
