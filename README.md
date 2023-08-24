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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: https://github.com/shoproizoshlo/nft-preview-card-component-main
- Live Site URL: https://sue-nft-preview-card-component.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to make a hover image and add overlays

To see how you can add code snippets, see below:

```html
<div class="image">
  <img src="./images/image-equilibrium.jpg" alt="image equilibrium" />
  <div class="overlay">
    <span class="icon"><img src="./images/icon-view.svg" alt="" /></span>
  </div>
</div>
```

```css

.image {
  position: relative;
  display: inline-block;
}
.image img {
  display: block;
  width: 100%;
  height: auto;
}
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: hsl(178, 100%, 50%, 0.5);
  opacity: 0;
  transition: opacity 0.3s ease-in-out;*/
  display: flex;
  align-items: center;
  justify-content: center;
}

.icon {
  font-size: 2rem;
  color: white;
}

.image:hover .overlay {
  opacity: 1;
}
```

### Useful resources

- [From hsl to rgb](https://htmlcolors.com/hsl-to-rgb) - This helped me convert from hsl to rgb when I created box shadows.

## Author

- Website - [Sue Brechko](https://sue-brechko-front-end-dev.netlify.app/)
- Frontend Mentor - [@shoproizoshlo](https://www.frontendmentor.io/profile/shoproizoshlo)
- Twitter - [@suereact](https://www.twitter.com/suereact)
