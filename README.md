# project0

CS50W Project 0
Completed by Andrew Coad, 15.02.20

This is a website I created for my dog, Gary.

A Bootstrap navbar is located at the top of each page:
  -index.html is the homepage, offering an introduction and image.
  -gallery.html is a photo gallery of Gary in cool places.
  -treats.html includes an image and three videos of Gary eating things he found.
  -data.html includes a table of Gary's dog friends and an image.

Three of the four pages utilize the columns from Bootstrap's grid model. index.html instead uses a media query to resize the welcome message and photo depending on the screen size.

Sass was utilized (in styles.scss) in a number of ways:
  -variables were used for the various colors
  -nesting was used for the images and video in the Bootstrap grid containers
  -the table cells inherited several properties from %table-cells while having different background colors.
