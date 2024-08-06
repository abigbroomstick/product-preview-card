# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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
This is a front-end challenge from Frontend Mentor. The task is to build out a product preview card and to make it as similar as possible to the original design.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop version](./Screenshot/Screenshot%20(Desktop%20version).png)
![Desktop version - Active](./Screenshot/Screenshot%20(Desktop%20version-active).jpg)
![Mobile version](./Screenshot/Screenshot%20(Mobile%20version).png)

### Links

- Solution URL: [https://github.com/abigbroomstick/product-preview-card](https://github.com/abigbroomstick/product-preview-card)
- Live Site URL: [https://abigbroomstick.github.io/product-preview-card/](https://abigbroomstick.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use BEM for my mark-up language as well as how I can best design for accessibility using visual hidden pattern for screen reader users without affecting the look of the page. 

```html
<h1>Some HTML code I'm proud of</h1>
<div class="flex-group">
        <p class="product__price">
          <span class="visually-hidden">Original price:</span>
          $149.99
        </p>
        <p class="product__original-price">
          <span class="visually-hidden">Original price:</span>
          <s>$169.99</s>
        </p>
      </div>
```
```css
.proud-of-this-css {
  .btn {
    cursor: pointer;
    
    text-decoration: none;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    gap: 0.75rem;

    border: 0;
    border-radius: 0.5rem;
    padding: 0.5em 1.5em;
    background-color: var(--clr-primary-400);
    color: white;
    font-weight: var(--fw-bold);
    font-size: 0.925rem;
}

.btn[data-icon="shopping-cart"]::before {
    content:"";
    width: 15px;
    height: 16px;
    background-image: url("images/icon-cart.svg");
}

.btn:is(:hover, :focus) {
    background-color: var(--clr-primary-500);
}
}
```

### Continued development

In the future, I want to use my experience building this component to build out a commercial website with product preview cards similar to this challenge.

### Useful resources

- [The HTML picture element explained [ Images on the web part 3 ]](https://www.youtube.com/watch?v=Rik3gHT24AM) - This helped me learn how to access different image sources to swap images that suit best for desktop or mobile. I really liked this pattern and will use it going forward.

## Author

- Github - [@abigbroomstick](https://github.com/abigbroomstick)
- Frontend Mentor - [@abigbroomstick](https://www.frontendmentor.io/profile/abigbroomstick)
- Facebook - [@Nam Nguyen](https://www.facebook.com/nam.nguyenbathanh/)

## Acknowledgments

Ashleynguci- she gave me huge motivation to learn web development :D
Colt Steele- best Udemy Front-End class I've taken so far
Kevin Powell- a great source for learning web development for FREE!
Nheo Hi- my lovely girlfriend who puts up with me every time I stayed up late to code.
