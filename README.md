# Frontend Mentor - Product preview card component solution

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](solution.jpg)


### Links

- Solution URL: [Add solution URL here](https://shemjay.github.io/product-preview-card-component-responsive/)
- Live Site URL: [liev site URL:](product-preview-card-component-fem.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design

### What I learned

I learned how to add responsive css breakpoints to code. While mine are unbelievably bad right now. Like abysmally bad, I am still very proud I stuck with it and did my best.

I also learned how to change a background image in css by loading them both in HTML and then setting one to dsiplay none and the other to display block.


```html
<div class = "img-container"> <!-- contains the site image-->
            <img src = "images/image-product-desktop.jpg" alt = "A bottle of perfume" class = "desktop-img">
            <img src = "images/image-product-mobile.jpg" alt = "A bottle of perfume" class = "mobile-img">
        </div>
```

```css
@media screen and (max-width: 992px) {
    .flex-container {
        width: 60%;
        height: 80%;
    }
}
```

### Continued development

1 . I need to work on adding responsive breakpoints to layouts 
2 . Adding image srcsets to code. I failed to get it to work here

## Author

- Frontend Mentor - [@shemjay](https://www.frontendmentor.io/profile/shemjay)
- Twitter - [@shemstack](https://www.twitter.com/shemstack)



