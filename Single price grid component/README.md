# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Screenshot

![](./screenshots/desktop.PNG) ![](./screenshots/mobile.PNG)

## My process

### Built with

- HTML5
- CSS3
- CSS Flexbox
- Mobile-first workflow

### What I learned

- Flexbox
- Positioning with flexbox
- Mobile-first workflow
- Responsive design

Solution for assigning height to a child element where the parent element only has min-height specified:

```css
.card {
        width: 50%;
        min-height: 70vh;
        display: flex;
        flex-direction: column;
    }

    .card-top {
        height: 50%;
        flex: 0.5;
    }

    .card-bottom {
        display: flex;
        height: 50%;
        flex: 0.5;
    }
```

### Continued development

- Continue learning about flexbox
- Continue learning flexbox positioning
- Continue learning responsive design

### Useful resources

- [CSS Tutorial - Zero to Hero (Complete Course)](https://www.youtube.com/watch?v=1Rs2ND1ryYc&t=12783s) - This CSS course helped me to learn and understand the basics of Flexbox and revise other CSS concepts.