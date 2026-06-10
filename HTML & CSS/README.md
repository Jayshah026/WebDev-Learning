```## HTML BASIC

<!DOCTYPE html> : Tells the browser that this document is an HTML5 document.

<html> : Root element of the webpage. Everything is written inside this tag.

<head> : Contains webpage information that is not visible on the page.

<body> : Contains all visible content of the webpage.

<title> : Sets the name of the webpage shown in the browser tab.

<meta charset="UTF-8"> : Allows the webpage to display all characters and symbols properly.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> : Makes the website responsive on mobile devices.

<link rel="stylesheet" href="style.css"> : Connects the HTML file with a CSS file for styling.

<script src="script.js"></script> : Connects the HTML file with a JavaScript file for functionality.

<h1> : Main heading of the webpage.
<h2> : Sub-heading.
<h3> : Smaller sub-heading.
<h4> : Smaller sub-heading.
<h5> : Smaller sub-heading.
<h6> : Smallest heading.

<p> : Used to write paragraphs and normal text content.

<br> : Moves content to the next line.

<hr> : Creates a horizontal dividing line.

<b> : Makes text bold.

<strong> : Marks text as important and displays it in bold.

<i> : Makes text italic.

<em> : Adds emphasis to text and displays it in italic.

<u> : Underlines text.

<a href=""> : Creates a clickable link to another page or website.

<img src="" alt=""> : Displays an image on the webpage.
src : Specifies the image location.
alt : Alternative text shown if the image cannot load.

<ul> : Creates an unordered (bullet point) list.

<ol> : Creates an ordered (numbered) list.

<li> : Represents a single item inside a list.

<div> : Generic container used to group elements for styling and layout.

<span> : Used to style or manipulate a small part of text.

<form> : Creates a form for collecting user input.

<input> : Allows users to enter data.

<input type="text"> : Text input field.

<input type="password"> : Password input field.

<input type="email"> : Email input field.

<input type="number"> : Number input field.

<input type="date"> : Date picker input field.

<input type="checkbox"> : Checkbox input field.

<input type="radio"> : Radio button input field.

<label> : Provides a label or description for an input field.

<button> : Creates a clickable button.

<textarea> : Allows users to enter multiple lines of text.

<select> : Creates a dropdown menu.

<option> : Represents an option inside a dropdown menu.

<table> : Creates a table.

<tr> : Creates a table row.

<th> : Creates a table header cell.

<td> : Creates a table data cell.

<header> : Represents the top section of a webpage.

<nav> : Contains navigation links.

<main> : Contains the main content of the webpage.

<section> : Groups related content together.

<article> : Represents independent content such as blog posts or news articles.

<aside> : Contains sidebar or extra content.

<footer> : Represents the bottom section of a webpage.

<!-- Comment --> : Adds comments in HTML that are not displayed on the webpage.

iframe : Embeds another webpage, video, map, or external content inside the webpage.

audio : Embeds audio files into the webpage.

video : Embeds video files into the webpage.

source : Specifies media files for audio or video elements.

figure : Groups images, diagrams, or illustrations with captions.

figcaption : Adds a caption to a figure element.

details : Creates a collapsible section that users can open and close.

summary : Defines the visible heading of a details element.

mark : Highlights text with a colored background.

code : Displays code snippets.

pre : Preserves spaces and line breaks exactly as written.

sup : Displays superscript text.

sub : Displays subscript text.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
## CSS 

/* CSS Connection */

<link rel="stylesheet" href="style.css"> : Connects the HTML file with a CSS file.

/* Selectors */

* {} : Selects all elements on the webpage.

body {} : Selects the body element.

.classname {} : Selects elements with a specific class.

#idname {} : Selects an element with a specific ID.

h1 {} : Selects all h1 headings.

div p {} : Selects all p tags inside div tags.

div, p {} : Selects multiple elements at once.

/* Colors */

color: red; : Changes text color.

background-color: blue; : Changes background color.

opacity: 0.5; : Makes an element transparent.

/* Text Styling */

font-size: 20px; : Changes text size.

font-family: Arial; : Changes font style.

font-weight: bold; : Makes text bold.

font-style: italic; : Makes text italic.

text-align: center; : Aligns text horizontally.

text-decoration: none; : Removes underline from links.

text-transform: uppercase; : Converts text to uppercase.

line-height: 1.5; : Controls spacing between lines.

letter-spacing: 2px; : Controls spacing between letters.

/* Width & Height */

width: 300px; : Sets element width.

height: 200px; : Sets element height.

max-width: 100%; : Maximum allowed width.

min-height: 100px; : Minimum allowed height.

/* Margin */

margin: 20px; : Space outside an element.

margin-top: 10px; : Top outer space.

margin-right: 10px; : Right outer space.

margin-bottom: 10px; : Bottom outer space.

margin-left: 10px; : Left outer space.

margin: 10px 20px; : Top-Bottom | Left-Right.

margin: auto; : Centers block elements horizontally.

/* Padding */

padding: 20px; : Space inside an element.

padding-top: 10px; : Top inner space.

padding-right: 10px; : Right inner space.

padding-bottom: 10px; : Bottom inner space.

padding-left: 10px; : Left inner space.

/* Border */

border: 2px solid black; : Creates a border.

border-radius: 10px; : Creates rounded corners.

border-color: red; : Changes border color.

border-width: 5px; : Changes border thickness.

/* Display */

display: block; : Element takes full width.

display: inline; : Element takes only required width.

display: inline-block; : Inline element with width and height support.

display: none; : Hides the element.

display: flex; : Enables Flexbox layout.

display: grid; : Enables Grid layout.

/* Positioning */

position: static; : Default position.

position: relative; : Moves relative to its normal position.

position: absolute; : Positions relative to nearest positioned parent.

position: fixed; : Stays fixed while scrolling.

position: sticky; : Sticks when scrolling reaches a point.

top: 10px; : Moves element from top.

right: 10px; : Moves element from right.

bottom: 10px; : Moves element from bottom.

left: 10px; : Moves element from left.

z-index: 10; : Controls stacking order.

/* Flexbox */

display: flex; : Activates Flexbox.

flex-direction: row; : Horizontal layout.

flex-direction: column; : Vertical layout.

justify-content: center; : Horizontal alignment.

align-items: center; : Vertical alignment.

gap: 20px; : Space between flex items.

flex-wrap: wrap; : Allows items to move to next line.

/* Grid */

display: grid; : Activates CSS Grid.

grid-template-columns: 1fr 1fr; : Creates columns.

grid-template-rows: auto; : Creates rows.

gap: 20px; : Space between grid items.

/* Background */

background-image: url("image.jpg"); : Adds background image.

background-size: cover; : Covers entire element.

background-repeat: no-repeat; : Prevents image repetition.

background-position: center; : Centers background image.

/* Images */

object-fit: cover; : Fits image without distortion.

object-position: center; : Positions image inside container.

/* Cursor */

cursor: pointer; : Changes cursor to hand icon.

cursor: not-allowed; : Shows restricted cursor.

/* Shadows */

box-shadow: 0px 0px 10px black; : Adds shadow around element.

text-shadow: 2px 2px 5px black; : Adds shadow to text.

/* Overflow */

overflow: hidden; : Hides extra content.

overflow: scroll; : Adds scrollbars.

overflow: auto; : Adds scrollbars only when needed.

/* Transitions */

transition: 0.3s; : Smooth animation effect.

transition: all 0.3s ease; : Animates all changes smoothly.

/* Transform */

transform: scale(1.1); : Enlarges element.

transform: rotate(45deg); : Rotates element.

transform: translateX(50px); : Moves horizontally.

transform: translateY(50px); : Moves vertically.

/* Hover Effects */

:hover : Applies styles when mouse hovers.

Example:
button:hover {
    background-color: blue;
}

/* Animations */

@keyframes animationName {} : Defines animation.

animation: slide 2s infinite; : Runs animation continuously.

/* Lists */

list-style: none; : Removes bullets from lists.

/* Visibility */

visibility: hidden; : Hides element but keeps space.

visibility: visible; : Shows element.

/* Common Units */

px : Fixed pixels.

% : Percentage of parent element.

vw : Percentage of viewport width.

vh : Percentage of viewport height.

rem : Relative to root font size.

em : Relative to parent font size.

/* Most Used CSS Properties */

color
background-color
font-size
font-family
font-weight
width
height
margin
padding
border
border-radius
display
flex
justify-content
align-items
gap
position
top
left
right
bottom
z-index
box-shadow
text-align
cursor
transition
transform
overflow
