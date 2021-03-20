# Frontend Mentor - Ping coming soon page solution

This is a solution to the [Ping coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ping-single-column-coming-soon-page-5cadd051fec04111f7b848da). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Submit their email address using an `input` field
- Receive an error message when the `form` is submitted if:
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say _"Please provide a valid email address"_

### Screenshot

![](./design/FinalScreenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/ping-coming-soon-page-html-and-css-HfOfh1WlY](https://www.frontendmentor.io/solutions/ping-coming-soon-page-html-and-css-HfOfh1WlY)
- Live Site URL: [https://frontentmentor-ping-coming-soon-page.netlify.app/](https://frontentmentor-ping-coming-soon-page.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The primary lesson I learned building this landing page is how to show error states for form inputs without JavaScript. I found an article on [CSS-Tricks on Form Validation UX in HTML and CSS](https://css-tricks.com/form-validation-ux-html-css/) that illustrates how to use the `:placeholder` pseudo-class to check if an input is showing a placeholder value. With this, I am able to style the input to show when the value doesn't match the validation without it showing the error before a value was entered.

To see how you can add code snippets, see below:

```css
/* Changes the color of the input's border when the input is not empty, not in focus, and isn't valid */
form input:invalid:not(:focus):not(:placeholder-shown) {
  border-color: var(--lightRed);
}
```

## Author

- Website - [Will Luft](https://www.willluft.com)
- Frontend Mentor - [@wdluft](https://www.frontendmentor.io/profile/wdluft)
- Twitter - [@IAmWillDL](https://twitter.com/IAmWillDL)
