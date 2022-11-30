# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### Screenshots

#### Desktop

![](./images/desktop.png)

#### Mobile

![](./images/mobile_view.png)

### Links

- Solution URL: [github repo](https://github.com/nicolasfig/stats-preview-card-component)
- Live Site URL: [Stats card component](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Using flexbox and media queries to change the alignment of items depending on the screen size
- Hoy to add a overlay to tint an image

```css
.card {
  flex-direction: column;
  margin: 10rem 5rem;
}

.overlay {
  min-width: 530px;
  min-height: 375px;
  background-color: var(--soft-violet);
  mix-blend-mode: multiply;
}
```

### Continued development

I want to focus on flexbox and how to use it effectively

### Useful resources

- [Mix blend mode (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - Useful for adding color to the image
- [Flexbox Malven](https://flexbox.malven.co/) - Really helpful cheatsheet for flexbox

## Author

- Frontend Mentor - [@nicolasfig](https://www.frontendmentor.io/profile/nicolasfig)
