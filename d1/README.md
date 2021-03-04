# Learning Objectives -  Browser Basics

1. ## Explain the difference between the BOM (browser object model) and the DOM(document object model).
  1. The DOM is the API used to access the elements inside the document
  2. The BOM is a larger representation of everything provided by the browser, including the current document
  
  - DOM(Document Object Model):
    - ![dom-example](../images/dom-example.png)
    - Interface that allows us to dynamically access and update the content, structure and style of a website
    - JS is the client-side scripting language that connects to the DOM in a browser
    - Defines HTML elements as objects and gives them properties, methods, and events
  
  - BOM(Browser Object Model):
    - ![bom-example](../images/bom-example.jpg)
    - Larger representation of everything provided by the browser, including the current document, location, history, frame, and any other functionality the browser may expose to JS. 
<br>
<br>
<br>

2. ## Given a diagram of all the different parts of the browser, identify each part.
  - ![browser-diagram](../images/browser-diagram.png)
 
    1. The User Interface
      - Everything the user interacts with, such as the address bar, back/forward buttons, bookmarks, etc..
      - Everything except page content
  
    2. Browser Engine
      - Manages interactions between the User Interface and the rendering engine
   
    3. Render Engine
      - Displays the requested page content
      - Parses HTML and uses CSS to build render tree and display content



3. Use the Window API to change the innerHeight of a user's window.
4. Identify the context of anonymous functions running in the browser (the window).
5. Given a JS file and an HTML file, use a script tag to import the JS file and execute the code therein when all the elements on the page load.
6. Explain the browser's main role in the request/response cycle.
7. Identify, examine, and delete cookies for a given website using the Chrome Developer Tools.
