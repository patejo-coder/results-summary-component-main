# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot/Frontend%20Mentor%20Results%20summary%20component%20-%20Computer.png)
![](./screenshot/Frontend%20Mentor%20Results%20summary%20component%20-%20Mobile%201.jpg)
![](./screenshot/Frontend%20Mentor%20Results%20summary%20component%20-%20Mobile%202.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: (https://patejo-coder.github.io/results-summary-component-main/)

## My process

I demarcated all the elements on the page and defined the way I would create my Layout, after defining the step by step I would follow, I started styling one item at a time, going from left to right.

In this challenge in question, what made it most difficult for me was making :Hover increase the <DIV> and as a consequence it activated the Opacity of the image that was hidden in the <DIV>.

### Built with

- Semantic HTML5 markup
- CSS (:Hover, .Scale, Opacity, Transisiton)
- Flexbox
- CSS Grid

### What I learned

In this challenge in question I used the display grid to define the positioning of the elements, and something I learned and was very proud of was the use of: Hover to change the properties of the elements when hovering the mouse over them, in addition to the use of propiedae. Scale which was also of great help for the interactivity I created on the page.

These properties made some very charming effects possible.

```css
.proud-of-this-css {
  #orange {
    background-color: hsl(0, 100%, 67%, .09);
    transition: .5s;
}

#orange:hover {
    scale: 1.1;
}

#orange img {
    opacity: 0;
    transition: 1s;
}

#orange:hover img {
    opacity: 1;
}
}
```

### Continued development

I want to continue developing my knowledge about properties that can contribute to a good styling of the website, a good example of this is the use of :HOVER which allows me to make some effects that in my case so far are simple, but which are also very effective .

## Author

- Frontend Mentor - [@patejo-coder](https://www.frontendmentor.io/profile/patejo-coder)
- Instagram - [@patejo_sama](https://www.instagram.com/patejo_sama/)
