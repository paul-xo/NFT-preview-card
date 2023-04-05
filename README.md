# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![active-state](./screenshots/active%20states.png.jpg)
![desktop-view](./screenshots/desktop%20view.png.png.jpg)
![mobile-view](./screenshots/mobile%20view.png.png.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```html
<section class="img">
  <img src="images/image-equilibrium.jpg" alt="image" />
  <div class="view"><img src="images/icon-view.svg" alt="icon" /></div>
</section>
```

```css
.img {
  position: relative;
}
.img img {
  width: 100%;
  border-radius: 10px;
}
.img:hover .view {
  display: flex;
  cursor: pointer;
}
.view {
  display: none;
  justify-content: center;
  align-items: center;
  position: absolute;
  right: 0;
  top: 0;
  width: 100%;
  height: 99%;
  background: hsla(178, 100%, 50%, 0.5);
  border-radius: 10px;
}
.view > img {
  opacity: 100%;
  width: 15%;
  display: block;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

## Author

- Frontend Mentor - [@paul-xo](https://www.frontendmentor.io/profile/paul-xo)
- GitHub - [@paul-xo](https://www.twitter.com/paul-xo)
