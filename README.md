# Code Refactor 
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines


GIVEN a webpage meets accessibility standards
WHEN I view the source code

Right Click in your browser window to view the source code from inspect on firefox or windows Edge or use the google DevTools from settings more tools.

THEN I find semantic HTML elements
<article>  

WHEN I view the structure of the HTML elements
The !DOCTYPE Declaration 
<Head> <body> <main-content> <footer>

THEN I find that the elements follow a logical structure independent of styling and positioning
<link rel="stylesheet" href="./assets/css/style.css">

WHEN I view the image elements
THEN I find accessible alt attributes
<!--img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="search engine optimization" /-->

WHEN I view the heading attributes
THEN they fall in sequential order
<div> <lu> <li> <a>

WHEN I view the title element
THEN I find a concise, descriptive title