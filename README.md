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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Order Summary Card Screenshot](images/screenshot.png)

### Links

- Solution URL: [Order Summary Card](https://github.com/bachiito/Order-Summary-Card)
- Live Site URL: [Order Summary Card](https://bachiito.github.io/Order-Summary-Card/)

## My process

1. I wrote all the HTML and applied the [BEM naming convention](https://en.bem.info/methodology/) to it while I was at it.
2. Similarly, I styled the page from top to bottom.
3. Likewise, I fixed the bugs I founded.
4. Furthermore, I added and styled the [hover](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover) and [focus-visible](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible) pseudo classes.
5. In addition to that, I added the media queries.

### Built with

- HTML
- CSS
- Flexbox
- Responsive workflow withot the need of media queries to change the layout and with a mobile first approach.

### What I learned

The mayor thing I learned when building this project was how to make a div that fulls the viewport completely, to do that I used the [viewport basic units](https://www.sitepoint.com/css-viewport-units-quick-start/) VH and VW.

```css
.container {
  width: 100vw;
  height: 100vh;
  background-image: url("../images/pattern-background-desktop.svg");
  background-size: 100vw 50vh;
  background-color: #e0e8ff;
  background-repeat: no-repeat;
}
```

### Useful resources

- [Overflow CSS shorthand property](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)

This helped me to give the border radius to the card I used it because I had to hide the overflow caused by the image and card body borders, this property really came in handy.

## Author

- Frontend Mentor - [@bachiito](https://www.frontendmentor.io/profile/bachiito)
