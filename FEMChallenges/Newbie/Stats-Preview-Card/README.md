# Frontend Mentor - Stats Preview Card Component (Solution)

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

![](images/solution.png)

### Links

- Solution URL: [Click to go to Github Repo](./).
- Live Site URL: [Click to go to Github Page](https://GianK128.github.io/FEMChallenges/Newbie/Stats-Preview-Card).

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned more about the use of flexbox, HTML tags and CSS properties I didn't know of.

For example this part, the header image:
```HTML
<div class="header-image">
  <picture aria-hidden="true">
    <source media="(min-width: 600px)" srcset="images/image-header-desktop.jpg">
    <img src="images/image-header-mobile.jpg" alt="">
  </picture>
</div>
```
And its CSS part:
```CSS
.stats-card .header-image {
    background-color: var(--accent);
    border-radius: .3rem .3rem 0 0;
}
.stats-card .header-image img {
    display: block;
    width: 100%;
    mix-blend-mode: multiply;
}
```
Ended up being easier than expected, but had to look up some things to find the `mix-blend-mode` property.

### Continued development

Take important note of keep researching for different ways to work with CSS, different properties, etc.

### Useful resources

- [mix-blend-mode property](https://developer.mozilla.org/es/docs/Web/CSS/mix-blend-mode) - Really useful property for working with overlays or making an image work with certain color palette.
- [img HTML tag](https://developer.mozilla.org/es/docs/Web/HTML/Element/img) - More info about the image tag and its attributes.

## Author

- Frontend Mentor - [@GianK128](https://www.frontendmentor.io/profile/GianK128)
