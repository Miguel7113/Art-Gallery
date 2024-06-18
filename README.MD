# HTML

1. Define the content structure : HTML uses tags / elements to define the structure (the layout and the content a user can see , paragraph, button, image, video) of the webpage

SYntax of HTML

-







2.Semantics : HTML provides semantics tags that provide specific meaning to content : Search Engine Optimization :
<header></header> : Heading section of the webpage
<footer></footer> : defines the bottom section of a page
<nav></nav> : navigation

3. Hyperlinks : HTML allows the linking of pages , external resources and internal recources through hyperlink tags <a> tag : anchor tag ,  <link>

4. Forms and Inputs : Collect user input and interact with backend services 
<form>
     <input/> email
     <input> password
     <button>Login<button>
</form>

comment tags are used to write notes with ocidng scripts
<!--write comment-->

###### CSS (Cascading Style Sheets)
- used to style and layout the web content structured by HTML 

1. Design and layout : controlling the visual appearance of a page
2. Responsive Design : CSS will allow us to adapt to different screen sizes and devices making the content accessible through all platforms : media queries and flexible grid layouts
3. Animations and Effects : creating visual effects (transitions) : JS is more friendly .

Syntax of CSS
Selectors : Element Name (p, button), elements id (#nameofid), class selector ( .nameofclass )


selector {
    stylingproperty : value
}

p {
    color: red;
}


### How we write CSS
1. External CSS : LInk a html file to an external css file : ;inked using the LINK tag
2. Internal CSS : Write css code inside the html document  : using the <style></style>
3. Inline CSS : Write 