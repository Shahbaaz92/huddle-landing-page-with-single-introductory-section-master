# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://github.com/Shahbaaz92/huddle-landing-page-with-single-introductory-section-master)
- Live Site URL: [Add live site URL here](https://shahbaaz92.github.io/huddle-landing-page-with-single-introductory-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- responsive

### What I learned

Using media queries to increase responsiveness of the site.

```css
@media screen and (max-width: 1200px) {
  h1 {
    font-size: 2rem;
    line-height: 40px;
  }
}
@media screen and (max-width: 1000px) {
  h1 {
    font-size: 1.5rem;
  }
  p {
    font-size: 16px;
  }
}
@media screen and (max-width: 800px) {
  .container {
    background: url("./images/bg-mobile.svg");
    background-size: cover;
    background-repeat: no-repeat;
  }
  main {
    flex-direction: column;
    align-items: center;
    text-align: center;
    width: 100%;
    height: auto;
    gap: 0;
  }
  main div {
    width: 100%;
    height: 400px;
    background-size: contain;
    background-position-x: center;
  }
  main section {
    width: 100%;
    align-items: center;
  }
  footer {
    margin-top: 100px;
    padding-bottom: 100px;
    justify-content: center;
  }
}

@media screen and (max-width: 550px) {
  header img {
    width: 100px;
  }
  main div {
    height: 300px;
  }
}
@media screen and (max-width: 410px) {
  main div {
    height: 200px;
  }
}
```

### Continued development

I would like to freely use media queries and be efficient in responsiveness.

### Useful resources

- [Font Awesome](https://fontawesome.com/) - This helped me for with brand logos.
- [Google fonts](https://fonts.google.com/) - I got all my fonts from here.

## Author

- Website - [Shahbaaz Athhar](https://github.com/Shahbaaz92)
- Frontend Mentor - [Shahbaaz Athhar](https://www.frontendmentor.io/profile/Shahbaaz92)
