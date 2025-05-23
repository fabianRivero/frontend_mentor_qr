# Frontend Mentor - QR code component solution

This is a solution to the QR code component challenge on Frontend Mentor.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![Mobile design](./design/mobile-design.jpg)

![Desktop design](./design/desktop-design.jpg)


### Links

- Live Site URL: [Live project](https://qr-component-front.netlify.app/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox

### What I learned

I learned to center block elements with Flexbox.
Image elements are originally inline elements. To center them within their parent, it's important to set them to display: block and use margin: 0 auto;

```css
  #body{
    background-color: hsl(212, 45%, 89%);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
   }

    img{
   width: 100%;
    display: block;
    margin: 0 auto;
    border-radius: 20px;
  }
```