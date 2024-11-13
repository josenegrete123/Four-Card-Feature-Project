# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/FourCardFeatureSolution.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://josenegrete123.github.io/Four-Card-Feature-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
      <section class="section first">
        <h1 class="title">Supervisor</h1>
        <p class="body">Monitors activity to identify project roadblocks</p>
        <img src="images/icon-supervisor.svg" alt="magnifying glass image" class="section__image">
      </section>
      <section class="section second">
        <h1 class="title">Team Builder</h1>
        <p class="body">Scans our talent network to create the optimal team for your project</p>
        <img src="images/icon-team-builder.svg" alt="house image" class="section__image">
      </section>
```
```css
.container {
        display: grid;
        grid-template-columns: repeat(6, 1fr);
        grid-template-rows: repeat(4, 1fr);
    }
```

### Continued development

Work more on inclusion of Flexbox and CSS grid.

## Author

- Website - [Jose Negrete](https://github.com/josenegrete123)
- Frontend Mentor - [@josenegrete123](https://www.frontendmentor.io/profile/josenegrete123)
