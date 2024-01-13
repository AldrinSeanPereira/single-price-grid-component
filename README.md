# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Single price grid component for Desktop](images/Single-price%20grid%20component%20for%20Desktop.png)


### Links

- Solution URL: [link](https://github.com/AldrinSeanPereira/single-price-grid-component)
- Live Site URL: [link](https://heartfelt-bavarois-10d8d2.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This is the first project I made without needing to seek help

While creating this project I had to deal with:
- [**MOST IMPORTANT**] how to correct the code I have created
- how to arrange the second and third cards side by side
- had to figure out how to align the content of cards. Eventually I changed my code from `justify-content: space-between` to `justify-content: center`
- creating my own colors to match the design 

I also learned it takes around 4 days per project and I am very passionate about getting the look perfect

```html
<section class="desktop-styling">

    <div class="card card-two">
    </div>

    <div class="card card-three">
    </div>

</section>
```
```css
.shadow {
    box-shadow: 0 10px 10px var(--color-box-shadow);
}

.card-two button {
  transition: transform 0.5s;
}

.card-two button:hover {
  transform: scale(1.1);
}
```

### Useful resources

- [CSS transitions and animations by freeCodeCamp](https://www.example.com) - Very lengthy but a good quick reference
- [CSS transitions by MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions) - Another reference to double check your knowledge

## Author

- LinkedIn - [Aldrin Sean Pereira](https://www.linkedin.com/in/aldrinseanpereira/)
- Frontend Mentor - [@AldrinSeanPereira](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [@AldrinSeanPereira](https://www.frontendmentor.io/profile/AldrinSeanPereira)

## Acknowledgments

My sincere thanks to Frontend Mentor and the help section of their discord server.
