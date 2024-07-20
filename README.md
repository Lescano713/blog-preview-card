# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page.
- The card is responsive to different screen sizes.

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Solution]()
- Live Site URL: [Live site](https://lescano713.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

<p>I learned how to use CSS custom properties (--colorBackground, --colorCard, etc.) to create a more maintainable and flexible styling system. Defining color values in one place allows for easy adjustments across the entire project. Additionally, I gained experience with @font-face to incorporate custom fonts with different weights, improving the typography of my design.</p>

```css
:root{
    --colorBackground: hsl(47, 88%, 63%);
    --colorCard: hsl(0, 0%, 100%);
    --colorParagraph: hsl(0, 0%, 50%);
    --colorTitles: hsl(0, 0%, 7%);
}
@font-face {
    font-family: 'Figtree';
    src: url('./assets/fonts/Figtree-VariableFont_wght.ttf') format('truetype');
    font-weight: normal;
}
```

<p>The hover and active states applied to .card demonstrate how to add interactive effects, such as scaling and changing box shadows, to enhance user experience.</p>


```css
.card:hover{
    transform: scale(0.9);
    cursor: pointer;
}
.card:active{
    box-shadow: -8px -9px 0 0 var(--colorTitles);
}
```


### Continued development
<p>Going forward, I plan to:</p>
<p>Improve Font Handling: Explore font formats and loading techniques to enhance performance and compatibility.
Refine Responsive Design: Ensure that the card and other components adapt seamlessly to various screen sizes and devices.
Leverage Advanced CSS Layouts: Experiment with CSS Grid for more complex and responsive layouts.
Enhance User Interactions: Continue to improve interactive elements with animations and transitions for a more dynamic user experience.</p>


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Linkedin - [@yourusername](https://www.twitter.com/yourusername)

