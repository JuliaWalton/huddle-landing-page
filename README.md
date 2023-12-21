# Frontend Mentor - Huddle landing page with single introductory section

![Design preview for the Huddle landing page with single introductory section](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out my solution for this challenge!

This is a solution to the [Huddle landing page with a single introductory section](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

## The challenge

Your challenge is to build out this landing page from the designs provided in the starter code.

Your users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Live Site URL: [https://juliawalton.github.io/huddle-landing-page/](https://juliawalton.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS3
- CSS Grid

### What I learned

This challenge was good for me to practice building responsive layouts quickly.

```css
@media (min-width: 1000px) {
  .product {
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin: clamp(3rem, 3vw, 3rem);
  }
  .icons {
    grid-column: 2 / 3;
    justify-content: right;
    position: relative;
    bottom: -50px;
  }
  .product-content {
    text-align: left;
    align-items: center;
    grid-template-rows: repeat(auto-fill, minmax(min(100px, 100%), 150px));
  }
}
```

## Author

- Website - [Julia's Portfolio](https://juliawalton.github.io/portfolio/)
- LinkedIn - [Julia Walton](https://www.linkedin.com/in/juliawalton/)
