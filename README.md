# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [https://github.com/hugo-marroquin/product-preview-card-component]
- Live Site URL: [https://product-preview-card-component-fm4.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

I learned how to change picture at different screen sizes using the picture element.

```html
<picture>
  <source
    media="(max-width: 37.5rem)"
    srcset="/images/image-product-mobile.jpg"
    alt=""
  />
  <img
    src="/images/image-product-desktop.jpg"
    alt="product image"
    class="img"
  />
</picture>
```

### Continued development

Continue learning about min-width, max-width and resizing images.
