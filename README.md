# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](finished-screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

This project allowed me to gain a better understanding of how the relative and absolute positioning works. It took a while to figure out how to position the illustration box, but eventually figured out how to place that by inserting another div which did not take any dimensions. The rest of the website was fairly easy to complete.

My JQuery code is working, but believe there is a much more compact way to write it out which I plan on figuring out.

```html
<div class="dummy-div">
  <div class="illustration-box-pic">
    <img class="box-img" src="images/illustration-box-desktop.svg" alt="illustration-box">
  </div>
</div>
```

```css
.dummy-div {
  position: relative;
}

.illustration-box-pic {
  position: absolute;
  top: 205px;
  left: -125px;
  z-index: 1;
}
```

### Continued development

I am still very new to JS/JQuery, and need more practice in it to become more efficient.
