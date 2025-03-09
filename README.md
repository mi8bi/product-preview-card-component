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

### Screenshot

![screenshot1.png](./screenshots/screenshot1.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/product-preview-card-component-GdyE-txWyhm)
- Live Site URL: [Live Site URL](https://product-preview-card-component-mu-eight.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
@font-face {
    font-family: "Montserrat";
    src: url("./fonts/Montserrat-Regular.ttf") format("truetype");
}

.card {
    position: absolute;
    top: 50%;
    left: 50%;
    display: flex;
    background-color: hsl(0, 0%, 100%);
    width: 400px;
    height: 300px;
    margin-left: -150px;
    margin-top: -150px;
    border-radius: 10px;
    overflow: hidden; /* 子要素がカードの角をはみ出さないようにする */
}

.cartBtn {
    display: flex;
    align-items: center;
    justify-content: center;
    column-gap: 8px;
    /* アイコンとテキストの間隔 */
    text-align: center;
    margin-top: 10px;
    font-family: "Fraunces";
    font-weight: 700;
    font-size: small;
    width: 100%;
    height: 40px;
    border: none;
    color: white;
    word-spacing: 0.2em;
    background-color: rgb(43, 148, 102);
    cursor: pointer;
}

```

### Continued development


### Useful resources


## Author

- GitHub - [mi8bi](https://github.com/mi8bi)
- Frontend Mentor - [@mi8bi](https://www.frontendmentor.io/profile/mi8bi)

## Acknowledgments
