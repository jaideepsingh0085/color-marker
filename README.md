# color-marker
![Screenshot 2023-09-06 233155](https://github.com/jaideepsingh0085/color-marker/assets/128147644/88f65414-96ce-4ffa-bb0a-18e86077d47e)
![Screenshot 2023-09-06 233207](https://github.com/jaideepsingh0085/color-marker/assets/128147644/62826bf1-c259-4271-afc9-5d4b25a86439)
![Screenshot 2023-09-06 233225](https://github.com/jaideepsingh0085/color-marker/assets/128147644/6496ba0c-8348-4a50-b2ae-9ab39b03b947)

Hosted Link : https://jaideepsingh0085.github.io/color-marker/

Html Description :
<!DOCTYPE html>: Declares the document type and version as HTML5.
<html lang="en">: Defines the HTML document with the English language.
<head>: Contains meta-information about the document.
<meta charset="utf-8">: Specifies the character encoding as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport settings for responsive design.
<title>Colored Markers</title>: Sets the title of the web page to "Colored Markers."
<link rel="stylesheet" href="./styles.css">: Links an external CSS stylesheet to style the page.
<body>: Contains the content of the web page.
<h1>CSS Color Markers</h1>: Displays a level 1 heading with the text "CSS Color Markers."
<div class="container">: Defines a container div for grouping elements.
<div class="marker red">, <div class="marker green">, <div class="marker blue">: Three colored marker divs with different classes for styling.
<div class="cap">: Represents the cap of each marker.
<div class="sleeve">: Represents the sleeve of each marker.

CSS Description :
h1: Selects all <h1> elements in the HTML document.
text-align: Specifies the text alignment property as center for <h1> elements.
.container: Selects elements with the class "container."
background-color: Sets the background color of the selected elements to white (RGB: 255, 255, 255).
padding: Adds 10 pixels of padding to the top and bottom and no padding to the left and right of the selected elements.

.marker: Selects elements with the class "marker."
width: Sets the width of the selected elements to 200 pixels.
height: Sets the height of the selected elements to 25 pixels.
margin: Sets a margin of 10 pixels on the top and bottom and auto margin on the left and right of the selected elements.

.cap: Selects elements with the class "cap."
width: Sets the width of the selected elements to 60 pixels.
height: Sets the height of the selected elements to 25 pixels.

.sleeve: Selects elements with the class "sleeve."
width: Sets the width of the selected elements to 110 pixels.
height: Sets the height of the selected elements to 25 pixels.
background-color: Sets the background color of the selected elements to a semi-transparent white (RGBA: 255, 255, 255, 0.5).
border-left: Adds a left border with a double line style, 10 pixels wide, and a dark semi-transparent color (RGBA: 0, 0, 0, 0.75).

.cap, .sleeve: Selects elements with both the "cap" and "sleeve" classes.
display: Sets the display property to inline-block for elements with both classes.

.red: Selects elements with the class "red."
background: Applies a linear gradient background with specified color stops.
box-shadow: Adds a box shadow with a specific color and blur.

.green: Selects elements with the class "green."
background: Applies a linear gradient background with specified color stops.
box-shadow: Adds a box shadow with a specific color and blur.

.blue: Selects elements with the class "blue."
background: Applies a linear gradient background with specified color stops.
box-shadow: Adds a box shadow with a specific color and blur.
