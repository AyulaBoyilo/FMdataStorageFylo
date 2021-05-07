# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [How I did it](#how-i-did-it)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMdataStorageFylo/)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMdataStorageFylo/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS and CSS3
- CSS Flexbox

### How I did it

The div.notice is positioned absolutely relative to the div.second. The arrow for the desktop is created using pseudo element and transparent borders.

```scss
.notice {
  position: absolute;
  top: -40px;
  right: 40px;
  left: auto;
  border-bottom-right-radius: 0;

  &::after {
    content: "";
    position: absolute;
    right: 0;
    bottom: -20px;
    height: 0;
    width: 0;
    border-top: 10px solid #fff;
    border-right: 10px solid #fff;
    border-bottom: 10px solid transparent;
    border-left: 10px solid transparent;
  }
}
```

### Useful resources

- [CSS Triangle](https://css-tricks.com/snippets/css/css-triangle/) - CSS-TRICKS How to create arrows with borders in CSS.

## Author

- Ayula Boyilo
