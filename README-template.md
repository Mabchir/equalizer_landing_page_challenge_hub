# Frontend Mentor - Equalizer landing page solution

This is my solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE).

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/Mabchir/equalizer_landing_page_challenge_hub)
- Live Site URL: [Netlify](https://your-live-site-url.com)

## My process

### Built with

- HTML
- CSS custom properties
- Flexbox

### What I learned

- how to position a background image

```css
body {
  background-image: url("./assets/bg-main-desktop.png");
  background-repeat: no-repeat;
  background-position: 0% 20%;
  background-size: cover;
  min-height: 100vh;
}
```

- how to make an image overflow

```css
.container {
  overflow: hidden;
}

.img {
  position: relative;
  bottom: 40px;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [StackOverFlow](https://stackoverflow.com/questions/2027657/overlapping-elements-in-css) - How to overlay different items in a div
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/background-size) - how to position a background image:
- [CSS Trisck](https://css-tricks.com/almanac/properties/o/overflow/) - how to make an image overflow

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
