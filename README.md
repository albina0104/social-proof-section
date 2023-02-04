# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshots

|Desktop|Mobile|
|:-:|:-:|
|![](./screenshots/screenshot1.png)|![](./screenshots/screenshot2.png)|

### Links

- Solution URL: [https://github.com/albina0104/social-proof-section](https://github.com/albina0104/social-proof-section)
- Live Site URL: [https://albina0104.github.io/social-proof-section/](https://albina0104.github.io/social-proof-section/)

## My process

### Built with

- **Semantic HTML5 markup**
- **CSS custom properties**

And I used several things for the first time in this project:

- **CSS Grid**

  I tried to use grid everywhere on the page, but in one place it did not behave as I wanted it to, and I realized it is the right task for Flexbox.

- **Sass**

  A great CSS preprocessor. I used nesting, functions, mixins, Sass variables, did some calculations.

- **NPM packages**

  - Sass - to compile .scss files to .css
  - [PostCSS](https://github.com/postcss/postcss-cli) with its plugins:
    - Autoprefixer - to add vendor prefixes to CSS
    - [Mqpacker](https://www.npmjs.com/package/mqpacker) - to pack same CSS media query rules into one (there are a lot of same queries generated from Sass code when we nest the queries inside selectors)
  - And some others which help to watch files and reload the browser when the files change, helpful during development

- **GitHub Actions**

  As a preparation for this and the next projects, I learned how to make GitHub Actions compile .scss files in this test repository: [Configuring GitHub Actions to compile .scss files](https://github.com/albina0104/test-scss). There is a README file there about what I learned regarding this topic.

### What I learned

New things described above :)

### Useful resources

- [2 Smartest Ways to Structure Sass](https://www.webdesignerdepot.com/2020/12/2-smartest-ways-to-structure-sass/) - Helped me to decide how to organize my Sass code
- [SASS Best Practices: 9 frontend tips for CSS preprocessors](https://www.educative.io/blog/sass-best-practices-frontend-coding-tips) - A nice overview of what is possible in Sass
- [8 Tips to Help You Get the Best out of Sass](https://www.sitepoint.com/8-tips-help-get-best-sass/) - An article with good pieces of advice
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Great to use as a cheat sheet
- StackOverflow answer [repeat css background image a set number of times](https://stackoverflow.com/a/52718403) - Helped to write a Sass function, so I did not have to calculate position of each image manually
- [Becoming a CSS Grid Ninja!](https://elad.medium.com/becoming-a-css-grid-ninja-f4c6db018cc1)
- [What is PostCSS? How to Use Plugins to Automate CSS Tasks](https://www.freecodecamp.org/news/what-is-postcss/) - A description of NPM's PostCSS plugins

## Author

- Frontend Mentor - [@albina0104](https://www.frontendmentor.io/profile/albina0104)
- GitHub - [albina0104](https://github.com/albina0104)
