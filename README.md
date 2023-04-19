# MyArchery
In this project, I've created an image carousel to showcase some items from my bow-making hobby. 

## Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Installing](#installing)
- [Usage](#usage)
- [Technologies](#technologies)
- [Acknowledgements/Sources Cited](#acknowledgements/sources_cited)
- [License](#license)

## About
My motive for this project was to challenge myself in learning more of Bootstrap 5's design templates but not only limited to BS5 Containers, Flex, and Carousels.

## Getting Started
In your index.html file: Get the HTMl5 boilerplate by using this [shortcut](https://backbencher.dev/html-boilerplate-code-visual-studio-code#:~:text=To%20try%20the%20shortcut%2C%20create,HTML5%20code%20to%20the%20file.).

## Installing

1. Get Bootstrap5 on your project with BootstrapCDN to link to Boostrap's default stylesheet. Get the source code [here](https://getbootstrap.com/docs/5.0/getting-started/download/). Place the link tag within the head section and the script tag before the closing body tag.

2.  Get Custom CSS to override Bootstrap5 CSS. First, make a file for your custom css, you can call this file custom.css. Then place this link tag here directly underneath the link to the default stylesheet:

![alt text](/BS_Override.png)

3. Get the favicon library to have access to use icons. To use the Font Awesome 4 icons, add the following line in the head section:

![alt text](/icons_library.png)

4. To make the "Contact Me" link scroll down to the Contact section of the page upon clicking:

* Add an opening section id in the Header in the "Contact Me" link to target a starting point in scrolling:

![alt text](/ScrollDown_Header.png)


* Then add a closing section id in the Footer section to set the footer as the address to scroll down to from the header:

![alt text](/ScrollDown-footer.png)

* And then create a JavaScript file(you can call it scroll.js) and write the following code to make the starting section id in the index.html file transition to the ending section id. The source of help for that code was found [here](https://codepen.io/nxworld/pen/OyRrGy). This makes the page scroll down to the footer once the "Contact Me" link is clicked:

![alt text](/ScrollDown_JS_code.png)



## Usage 
In this simple image carousel site, the user can:

**View slideshow of the images:** Clicking the left arrow will navigate toward the previous slide, the right arrow leads to the next slide. If no arrow is clicked, the carousel will automatically transition towards the next slide after the set interval of 5000 milliseconds(adjustable). To pause the slideshow, just leave the mouse hovering over anywhere on the carousel.

![alt](/Buttons.png)

**Instantly scroll down to the footer section of the page to view contact info:** Clicking the "Contact Me" link in the header will scroll all the way down to the footer.

![alt](/Contact_Link.png)

**Click and open the icons under the "Contact Me" section.**

![alt](/Contact_Logos.png)

## Technologies
* HTML5
* CSS
* Boostrap v5.2.3
* Favicons library v4.7.0


## Acknowledgements/Sources Cited
* Bootstrap Carousel - https://www.w3schools.com/bootstrap5/bootstrap_carousel.php
* Favicons Library - https://www.w3schools.com/html/html_favicon.asp
* Scroll Down Button - https://codepen.io/nxworld/pen/OyRrGy
* Footer Design - https://foolishdeveloper.com/simple-responsive-footer-design-using-html-and-css/
* Background Template - https://www.freepik.com/free-vector/flat-design-traditional-native-american-pattern_20826204.htm#query=native%20american%20background&position=2&from_view=keyword&track=ais

## License