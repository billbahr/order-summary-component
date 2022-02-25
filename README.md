# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Solution Screenshot](images/screenshot.png)


### Links

[Solution Repo](https://github.com/billbahr/order-summary-component)

[Live Site](https://billbahr.github.io/order-summary-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid

### What I learned

This challenge didn't have anything quite as challenging as the hover effect from the NFT Preview Card one, but I did learn some new things.

Centering the card in the viewport:
```css
main {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%)
}
```
Adding a drop shadow to the button:
```css
    filter: drop-shadow(0 1rem .5rem var(--paleblue));
```

I also continued improving my understanding of using Flexbox for various parts of the layout.

### Useful resources

- [CSS Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - I'm constantly referring back to this for help with Flexbox properties, plus CSS Tricks has lots of other helpful content.

## Author

- Website - [Bill Bahr](https://www.your-site.com)
- Frontend Mentor - [@billbahr](https://www.frontendmentor.io/profile/billbahr)
- Twitter - [@billbahr](https://www.twitter.com/billbahr)
