# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](/screenshots/social-proof-section.png) <br>
![](/screenshots/mobile-social-proof-section-p1.png) <br>
![](/screenshots/mobile-social-proof-section-p2.png)

### Links
- Live Site URL: [GitHub Pages](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Naming Convetions

### What I learned

How to use `::before` and `::after` in the body tag to display the background images

```css
body {
    font-family: 'League Spartan', sans-serif;
    position: relative;
    padding-top: 5rem;
    padding-bottom: 5rem;
}

body::before {
    content: url('/images/bg-pattern-top-mobile.svg');
    position: absolute;
    top: 0;
    left: 0;
}

body::after {
    content: url('/images/bg-pattern-bottom-mobile.svg');
    position: absolute;
    bottom: 0;
    right: 0;
}
```
### Continued development
I want to focus on building more components, tracking how much took me to build
each of the components and what are my strengths and weakness when it comes to
developing layouts.

I want to learn more about CSS Grid to further imporove my layout developments and
workflow.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/wellington-damasio)
