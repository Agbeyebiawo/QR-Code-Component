# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![](/Screenshot%20(70).png)




### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/home)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

Building this project, I learned how to add favicon in HTML, CSS media queries for responsive design, how to create custom CSS properties.  

To see how you can add code snippets, see below:

```html
    <link rel="shortcut icon" href="images/favicon-32x32.png" type="image/x-icon">

```
```css
:root{
    /* Colors */
   --WHITE: hsl(0,0%,100%);
   --LITE--GRAY: hsl(212,45%,89%);
   --GRAYISH--BLUE: hsl(220,15%,55%);
   --DARK--BLUE: hsl(218,44%,22%);
   --GRAYISH--BLUE--A: hsla(220,15%,55%,0.4);
   
   /* Fonts */
   --P--FONTS: 15px;
   --FAMILY: Outfit;
   --LITE--WEIGHT: 400;
   --BOLD--WEIGHT: 700; 
   
   /* Layouts */
   --MOBILE: 375px;
   --DESKTOP: 1440p;
}

/* Mobile Layout */
@media (max-width : 375px){
    body{
        display: flex;
        flex-flow: column wrap;
        justify-content: space-around;
        width: 100%;
        align-items: center;
        font-family: sans-serif;
    }

    .card{
        width: 87%;
    }
}
```


### Useful resources

- [Favicon W3schools](https://www.w3schools.com/html/html_favicon.asp) - This resource taught me how to add favicon to HTML. 
- [Font Face W3schools](https://www.w3schools.com/cssref/css3_pr_font-face_rule.php) - This resource taught me how to import custom fonts to CSS.
- [CSS Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This resource taught me how to use CSS media queries to build responsive layout across different view ports.


## Author


- Frontend Mentor - [@Agbeyebiawo](https://www.frontendmentor.io/profile/Agbeyebiawo)



