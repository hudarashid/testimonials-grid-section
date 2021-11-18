# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size


### Links

- Solution URL: [https://hudarashid.github.io/testimonials-grid-section/]


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid



### What I learned

Using grid to arrange "testimonial boxes" in a more easier way


```css
.grid {
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 50% auto;
  grid-template-areas: 
     "daniel daniel jonathan kira"
     "jeanette patrick patrick kira";
}
```


### Continued development

Continue to learn grid in a more comprehensive way



### Useful resources

- [https://css-tricks.com/snippets/css/complete-guide-grid/#prop-grid-column-row-start-end] - This site helping me for deeper understanding to GRID


## Author

- Frontend Mentor - [@hudarashid](https://www.frontendmentor.io/profile/hudarashid)
- Twitter - [@hudaMRashid](https://twitter.com/hudaMRashid)



