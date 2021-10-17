# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](https://i.postimg.cc/Px2WcvHT/Order-Summary-FM.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup

- CSS custom properties

- Flexbox

- CSS Grid

- Mobile-first workflow (Responsiveness)

### What I learned

1. While working on this i was focusing on Responsiveness of components and contents, like on desktop mode how this will be visible and on mobile view how i can re-arrange same thing without messing UI.

```css
@media (min-width: 768px) {
  .viewport {
    background: var(--background-color) url("./images//pattern-background-desktop.svg")
      no-repeat center top / contain;
  }
}
```

2.  Using CSS Shorthand properties to make CSS looks simpler and easy to understand like this,

```css
background: url("./images//icon-music.svg") no-repeat center center / contain;
```

### Continued development

As you can see this is created with just simple HTML and CSS, my focus will be to create same using [React.js](https://reactjs.org) library and to understand this process.
