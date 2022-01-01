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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop Preview](./design/desktop-preview.jpg)
![Active States](./design/active-states.jpg)
![Mobile Preview](./design/mobile-design.jpg)

### Links

- Solution URL: [GitHub Repo](https://github.com/nft-preview-card)
- Live Site URL: [Live Site](https://webster-nft-card-preview.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Before starting this project, I was a bit rusty with CSS since I didn't do any challenges for some time. But I found the challenge extremely refreshing.

To make the "View Icon" work on hover, I used absolute position and worked with opacity to show & hide the icon.

```css
.overlay-background {
  position: absolute;
  top: 0;
  left: 0;
  background-color: rgba(0, 255, 247, 0.5);
  opacity: 0;
  transition: 0.5s linear;
}

.overlay-background:hover {
  cursor: pointer;
  opacity: 1;
}
```

### Continued development

This was a simple component project from Front-End Mentor, so I did it just for some practice and to have some fun. So, I'll leave it with no further changes.

### Useful resources

- [CSS Tricks](https://www.css-tricks.com)

## Author

- Website - [Akshay Webster](https://www.akshaywebster.com)
- Frontend Mentor - [@akshaywebster](https://www.frontendmentor.io/profile/akshaywebster)
- Twitter - [@akshaywebster](https://www.twitter.com/akshaywebster)

## Acknowledgments

Thanks to Front-End Mentor for this project and for providing me with beautiful design files to make this project.
