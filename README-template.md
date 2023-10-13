# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Animation

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Learned to implement media-break-points for various elements.

To see how you can add code snippets, see below:

```html
<section class="sec-sect">
        <p class="first-p">PERFUM</p>

        <h1>Gabrielle Essence Eau De Parfum</h1>

        <p class="Sec-p">A floral, solar and voluptuous interpretation composed by Olivier Polge, 
        Perfumer-Creator for the House of CHANEL.</p>
        <div class="price">
          <h2>$149.99</h2> 
          <p>$169.99</p>
          </div>
      <button> <img src="./images/icon-cart.svg" alt="card">Add to Cart</button>
      </section>```
```css
@media only screen and (min-width: 376px){
    html{
        font-size: 16px;
    }
    
    main{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 35rem;
        min-height: 10vh;
        margin-top: 250px ;
    }
    .sec-sect{
        width: fit-content;
        margin-top: 0;
    }
  }```
```


### Continued development

Learnig Grid concept in next project.


## Author

- Website - Not yet
- Frontend Mentor - [@MjafarsadiqD](https://www.frontendmentor.io/profile/Ashraful-Fuqha)