# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./PC-screenshot.png)
![](./Mobile-screenshot.png)

### Links

-[Live Site](airdgo-stats-preview-main.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

How to use mix-blend-mode in order to put a layer over an image.

```html
<figure calss="desktop">
    <img class="image-desktop" src="images/image-header-desktop.jpg" alt="women at computer">
</figure>
```
```css
figure {
    background-color: var(--clr-primary-accent); /* set a background color for the image container */  
}

.image-mobile {
    display: block;
    mix-blend-mode: multiply;
    opacity: 0.8;
}
```

### Continued development

Defently want to use mix-blend-mode more. I think you could get some awesome designs.

### Useful resources

- [mix-blend-mode](https://www.w3schools.com/cssref/pr_mix-blend-mode.asp) - This helped me understand mix-blend-mode.

## Author

- Frontend Mentor - [@airdgo](https://www.frontendmentor.io/profile/airdgo)
