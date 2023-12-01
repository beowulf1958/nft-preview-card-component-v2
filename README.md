# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%20NFT%20preview%20card%20component.png)

### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/nft-card-made-with-bem-TvOpvu8pE3)
- Live Site URL: [Live site URL here](https://incandescent-lollipop-3a4de6.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [BEM](https://getbem.com/introduction/) - BEM

### What I learned

This is my second iteration on this project. The first one I shipped seems to have fallen apart after upload. Re-doing it allowed me to apply a few techniques I have learned since I first did it. I am now more comfortable with the ::after pseudo element.

```css
.card__image::after {
  position: absolute;
  top: 0;
  border-radius: 0.5rem;
  width: 13.5rem;
  height: 13.5rem;
  display: grid;
  place-items: center;
  content: url(images/icon-view.svg);
  background-color: hsl(215, 51%, 70%);
  opacity: 0;
}
.card__image:hover::after {
  opacity: 0.5;
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
