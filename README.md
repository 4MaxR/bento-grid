# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover states for interactive elements
- Navigate through a responsive bento grid layout
- Experience fluid typography and spacing across different viewport sizes

### Screenshot

![image](https://github.com/user-attachments/assets/a59cea32-1a67-4355-8ccd-703be24aa68c)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid and Flexbox
- Mobile-first workflow
- Modern CSS Features:
  - clamp() for fluid typography
  - CSS Grid areas
  - text-wrap: pretty
  - Custom properties for design tokens

### What I learned

Throughout this project, I gained valuable experience in several areas:

1.Advanced CSS Grid Layout:

```css
main {
  @media screen and (min-width: 768px) {
    grid-template-areas:
      "create social social time"
      "create manage maintain time"
      "write manage maintain time"
      "write growth followers followers";
  }
}
```

2.Fluid Typography using clamp():

```css
--fs-2xl: clamp(2.3328rem, 2.0827rem + 1.2504vw, 3.0518rem);
```

Responsive Design with Custom Properties:

```css
:root {
  --space-m: clamp(1.6875rem, 1.6223rem + 0.3261vw, 1.875rem);
}
```

const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Continued development

Areas I plan to focus on in future projects:

- Implementing more advanced animations and transitions
- Enhancing accessibility features
- Exploring CSS Container Queries
- Adding more interactive elements
- Optimizing performance further

### Useful resources

- CSS Grid Guide - Comprehensive guide for CSS Grid implementation
- Fluid Typography - Helped with implementing fluid type scaling
- Modern CSS - Great resource for modern CSS practices

## Author

- Website - [4MaxR](https://github.com/4MaxR)
- Frontend Mentor - [@4MaxR](https://www.frontendmentor.io/profile/4MaxR)
