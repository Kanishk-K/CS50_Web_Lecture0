index.html 
===========
index.html is the file that is the homepage of my website, it has links to the other three pages. The @media query in the css applies to this file, by shrinking the viewer the table will decrease in size and the font size for the title will decrease. This also contains the table object.

AboutMe.html
============
A very basic html page consisting of a "p" tag and a link back to index.html

MyExperience.html
=================
This is the html file that is perhaps the most complex out of the previous ones, it has bootstrap rows, columns and buttons in order to add style to the webpage. Furthermore, while the file does not have a @media query associated with it, the webpage uses the bootstrap grid model to make the webpage mobile responsive.

MyInterests.html
================
This html file contains a few lines of text as well as an image. While MyExperience.html has images for each button, this file has an explicit "img" tag and a larger image. While not using an @media query the image still scales to the size of the viewer.

HTML Requirements
================
Index.html contains a table object, MyExperience.html has the list objects and MyInterests.html has the image object.

Stylesheets
===========
My website has two stylesheets, style.css and ExperienceStyle.css. style.css styles more than five different elements while using the id and class selectors as well. The @media query is present in style.css.

Bootstrap
=========
Bootstrap is used primarily on MyExperience.html with its buttons and columns/rows.

SCSS
====
The MyExperience.scss file contains the imagewidth variable, with two instances of nesting, and an inheritence with @extend.
