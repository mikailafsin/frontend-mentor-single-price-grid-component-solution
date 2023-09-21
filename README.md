# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

**Mobile**
![](./screenshot/mobile-screenshot.png)

**Desktop**
![](./screenshot/desktop-screenshot.png)


### Links

- Solution URL: [GitHub](https://github.com/mikailafsin/frontend-mentor-single-price-grid-component-solution)
- Live Site URL: [Vercel](https://frontend-mentor-single-price-grid-component-solution.vercel.app)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - CSS pre-processor

### What I learned

I continued to practice sass pre-processor in this challenge.

**One of the scss code I wrote**
```scss
.price-grid-bottom-col-button {
  color: $lightGray;
  background-color: $brightYellow;
  text-align: center;
  width: 100%;
  padding: 1rem 0;
  border-radius: .375rem;
  border: none;
  outline: none;
  cursor: pointer;

  font: {
      weight: 700;
      size: .875rem;
  }

  &:hover {
      background-color: $darkGray;
  }
}
```

### Continued development

In future projects, I plan to write code with the BEM methodology, which is a style naming tradition, as well as the SASS pre-processor. Therefore, I will focus on learning the BEM methodology in future projects.

## Author

- Frontend Mentor - [@mikailafsin](https://www.frontendmentor.io/profile/mikailafsin)
- Instagram - [@mikail.afsin](https://www.instagram.com/mikail.afsin)