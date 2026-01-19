# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [solution](https://www.frontendmentor.io/solutions/nftpreviewcardcomponentmain-A3EaTE856j)
- Live Site URL: [live site](https://tarek-bari.github.io/nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

What I learned about this challenge is that I can separate the properties of specific elements inside same parent.
As I solve the hover problem with img element below:
I can controle img opacity separatly.
I extracted this solution from frontendmentor feedback, I really appreciate that.

```css
.card .image:hover {
  background-color: var(--Cyan);
}

.card .image img {
  border-radius: 0.4rem;
}

.card .image:hover img {
  opacity: 0.5;
}
```

### Continued development

I'm planning to use grid and animation also rest advanced features of CSS. In addition to learn SCSS.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) - This helped me for finding all css properties with full examples. I really liked this pattern and will use it going forward.
- [Josh Cameau Blog](https://www.joshwcomeau.com/css/center-a-div/) - This is an amazing article which helped me finally understand how to center a div with best way. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Tare Bari](https://tarek-bari.vercel.app/)
- Frontend Mentor - [@Tarek-Bari](https://www.frontendmentor.io/profile/Tarek-bari)

## Acknowledgments

Many thanks and appreciation to the users of @Frontendmentor especially @@hitmorecode and @@davidochoadev.
I was inspired to find a solution based on thier feedbacks.
