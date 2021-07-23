# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [https://github.com/Pow3rZ/profile-card-component]
- Live Site URL: [https://pow3rz.github.io/profile-card-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- SASS
- Flexbox
- Mobile-first workflow

### What I learned

It wasn't needed but i wanted to make background somewhat responsive and so i learned about relative positioning of multiple background images and aspect-ratio media query.


```css
@media screen and (max-aspect-ratio: 1 / 1) {
  html {
    background-size: 80vh 80vh, 80vh 80vh;
    background-position: left -40vh top -40vh, left 50vw top 50vh;
  }
}
```

### Useful resources

- [https://developer.mozilla.org/en-US/docs/Web/CSS/@media/aspect-ratio] - This is site expalining how aspect-ratio media query works.


## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/Pow3rZ]
