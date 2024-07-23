# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of Blog preview card](/assets/images/blog-preview-card-screenshot.jpg)

### Links

- Solution URL: [https://github.com/GitOfGod/blog-preview-card.git](https://github.com/GitOfGod/blog-preview-card.git)
- Live Site URL: [https://gitofgod.github.io/blog-preview-card](https://gitofgod.github.io/blog-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I changed from a static to a variable font file because the static files only contained higher weights, which were very different from the design prompt provided.

I intially struggled to achieve the desired 3D effect for the card. I tried using `border-style: outset`, but that still gave a 2D shape.

I also experimented with `box-shadow`, which added density to the shape, but the opacity didn't match the design prompt. After researching the `box-shadow` property on the W3Schools website, I set the blur to 0, which resulted in a block color.

Additionally, I encountered an issue where the illustration image overflowed into the padding of its parent container. Through research, I discovered that setting the `max-width` property helped keep the image within the confines of its parent div’s content section.

## Author

- Website - [@GitOfGod](https://github.com/GitOfGod/blog-preview-card.git)
- Frontend Mentor - [@GitOfGod](https://www.frontendmentor.io/profile/GitOfGod)
