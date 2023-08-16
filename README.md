# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)



## Overview

this challenge i have done using HTML/CSS. I tried Mobile first workflow this time and it is much better then Desktop first.This way i can design for mobile first which is easier then desktop one and then use media queries for desktop version.

### The challenge

The challenge was to build out this social proof section and get it looking as close to the design as possible. Users should be able to view the optimal layout for the section depending on their device's screen size.

### Screenshot

![Desktop Screenshot](/Screenshots/Screenshot%20Desktop.png.jpg)
![Mobile Screenshot 1](/Screenshots/ScreenShot%20Mobile%201.jpg)
![Mobile Screenshot 2](/Screenshots/ScreenShot%20Mobile%202.jpg)

### Links

- Live Site URL: [Live site](https://idyllic-madeleine-53e1a1.netlify.app/)

## My process

Firstly i made a rough blueprint of the site i figured out where to use what element and which element should be nested into other and which elements should have classes and ids. after making basic html and css for mobile i started on desktop design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

for the reviews and rating section it requires a layout with 3 divs and 3 divs have to positioned differently like one in left top, one in center,one in bottom right so for this i used CSS positioning properties.I used display relative and absolute as follows;-


```css
.wrapper {
  position:relative;
}
.leftChild{
  position:absolute;
  left:0;
  top:0;
}
.centreChild{
  position:absolute;
  left:50px;
  top:50px;
}
.rightChild{
  position:absolute;
  bottom:0;
  right:0;
}
```

### Continued development

I really wanted to used display grid in this challenge, i tried but no able tp get the desired result but i want to learn this property and use this in future projects.

### Useful resources

- [mdn web docs](https://developer.mozilla.org/en-US/) - This helped me in understanding different html and css properties.
- [w3sschools](https://www.w3schools.com/) - Always a good site for basics of HTML/CSS.

## Author

- Frontend Mentor - [@sourabh053](https://www.frontendmentor.io/profile/sourabh053)
- LinkdIn - [Sourabh Thakur](https://www.linkedin.com/in/sourabh-thakur-b71a68250/)
