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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: (https://github.com/OMallesDev/FeatureSelection)
- Live Site URL:](https://omallesdev.github.io/FeatureSelection/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I think the biggest takeaway was using and formatting CSS Grid layouts. Still not perfect but they are defniietly useful in situations like this challenge.

```css
main {
    height: 100vh;
    width: 100%;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: 10rem 1fr 1fr 1fr 1fr;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    grid-row-gap: 2rem;
}
```


### Continued development

I definitely want to keep working in grid layout for desktop projects. It's still on the difficult side for me so it's something I definitely want to get down into memory.

## Author

- Frontend Mentor - (https://www.frontendmentor.io/profile/omallesdev)
- Twitter - [(https://www.twitter.com/omallestv)
