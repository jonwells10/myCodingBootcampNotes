# myCodingBootcampNotes
Coding Bootcamp Notes

## This is my Readme file

### Terminal Commands:

#### cd
Change Directory. This changes the current working directory. 
Working Directory i sthe file path you are currently on in your terminal.

< some directory > can be any folder on your system.  If it doesn't start with / like for example Documents/Misc it means that your current Directory should have doucments.

If it isn't there, it will give you this error:
`-bash: cd: Documents: No such file or directory
`
### pwd
Stands for present working directory.  It lists the directory you are in.

### ls 
Lists all the files and directories in the current directory

### ls < some directory > list all the files and directories in some directory

### mkdir
makes a file in some directory 

### touch < filename > 
Creates a new file with name filename 

### rm < filename > 
removes or deletes a file

### rmdir < directory >
removes or deletes a directory 

### cp <targetfile> <destination file>
Copies a file from target to destination 

### mv <targetfile> <destination file>
Moves a file from target to destination 

## Cool Terminal Shortcuts
Up key: goes to the previous command 
Tab Key (while typing a file/folder name): Fills out the filename if it's there and unique

### Terminal Special Directories
~/ = user directory 
../ = one directory up (goes to parent diretory/folder)
./ = current directory
/ = root directory 


### GIT Commands
git clone  - copies an entire repo (to begin)
git add     - adds a file for inclusion in GIT
git commit  - notes a change to the local repo
git push    - sends changes to hosting service.
git pull    - downloads the freshest version
### GIT Directory
    /Documents/coding_class/myCodingBootCampNotes

### HTML Syntax (code grammar)
Tag = <h1> <a> or equivalnet 
attribute: a stands for anchor(means web link)
<a href="www.google.com"> Link <a/>

Self Closing tag:
<img src="img.png"> src = source

### Common Tags HTML
<h1> largest tag through <h5> smallest tag

### Containers
<html> wraps entire page
<head> wraps the heads of the page
<body >wraps the main content
<div> logical container
<p> paragraphs

### Others
<strong> bold
<img> images; <a href> links; <li> lists; <title> titles; <br> line break; <table> tables; <!-- --> Comments

HTML Tags here htt://www.w3schools.com/tags/

### Common UI (user interface)
<form> creates form section HTML
<input> 
<label>
<button>
<textarea>

### Stackoverflow 
Help search for solutions to coding issues

### CSS Syntax
selctor      property         value
a        { background-color:  yellow}

### Flow
every element is displayed is governed by a concept called "flow"

### Box Model
The box model wraps every CSS element in padding; border; and margin;
*Allows developers to modify spacing styles*

### CSS positioning
Orient elements different ways
Static - Default; falls wherever positioned 
Fixed - Fixed on screen does not move when screen moves
Relative - postion relative to parent element; inside container
Absolute - Fixed but scrolls with page

### How to learn
stack overflow
smashing magazine 
css-tricks
w3schools.com
design shack 
Css newbie
CodeShip

### Selection Layout vs Div
All web layouts inherently composed of containers, traditionally called "divs"
HTML5 introduced "sematic layouts" meaning divs could be given more meaningful names

### Classes vs IDs
Classes: (.classname) are to be used if the same style will be used on multiple HTML elements
IDs: (#idname) are to be used if a style is unique to that HTML element

### Chrome Developer Tools
Allows to real time show code and debug your web designs 
Open using: command+option+i

### Battle of Browsers
Chrome
Internet Explorer
Firefox
Safari 

Pages need to be cross-browser compatible

### Reset.css
Will reset all browser-specific css

### Typography 
-Visual aesthetic and emotional identy of the page 

Properties:
Line Height - Distance between lines of text
Font Size - Actual size of lettering.  At least 16px on modern pages
Line length - Not a css property but rather a standard. 50-75 characters per line on a desktop
Letter spacing - Spacing between ivdividual letters - avoid cramping
Sans-Serif vs Serif - SS fonts include small lines attached to the end strokes of letters, Serif is plane



### Google Fonts
Google Custom fonts available for free
fonts.google.com

### Pseudo Classes
CSS has keywords that can be added to selectors. These highlight the special states of a selected element 

Can add effects to buttons

Starts with a colon: hover is when over the button / focus is when you click the button/ active is after you click the button 

https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Pseudo-classes_and_pseudo-elements

### Bootstrap
Predefined css styling
http://getbootstrap.com

prebuilt templates


### Mobile Responiveness 
page changes as your decrease the page size
BootStrap has built in mobile response

### Bootstrap functionality 
gylphicon glyphicon-envelope puts an envelope in

UI Kit familarize yourself with features - able to copy snippets from the documentation to save time on creating elements yourself

### Basic Variables
variables are the nouns of programming
they are "things" (numbers, strings, booleans, etc.)
they are composed of variable names and values

### JavaScript Stuff
JavaScrpit is the "logic" of the page. Lets us interact with the page.

Basic Variables "Syntax"
console.log("ajajdjad" true);  console.log allows you to view inputs in the developer tools

var doYouRock = confirm("your message"); confirm - allows you to hit "ok" or "cancel"
var howMuchRock = prompt("your message") prompt - allows you enter a value when prompted

alert(doYouRock);
alert(howMuchRock): 


### IF/Else conditions
if (doYouRock) {
        alert("Message + howMuchRock")
}

else if (variableName){
    alert("message")
}

else (howMuchRock) {
        document.write("message here")
}

### Arrays

ArrayName: zooAnimals

var zooAnimals = ["Zebra", "Rhino", "Giraffe", "Owl"];

console.log(ZooAnimals[1]);

### Console.log
Used for troubleshooting javascript

Running console log to check an array
console.log(coolpeople[0])
console.log("Size: " + coolPeople.length)

### For Loops
allows you to create an console.log for an whole array

Logical Operators
|| = or (either could be true)
&& = and (both must be true)
