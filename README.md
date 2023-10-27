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

![Desktop Screenshot](/images/desktop.png)
![Mobile Screenshot](/images/mobile.png)



### Links

- Live Site URL: [live site](https://cpuening84169482.github.io/Order-Summary-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned that you can use the margin: 0 auto; application to center a div on the is parent, and generally speaking that is the body. I'm proud of the code below because it features the margin command. 


```css

    .grid-container
    {
        display: grid;
        margin: 0 auto;
        grid-template-areas: 
            'header'
            'main';
        
        background-color:  hsl(225, 100%, 98%);
        border-radius: 25px;
        text-align: center;
        width: 75%;
        height: 80%;
    }
```


### Useful resources

- [Scaling of SVG Backgrounds](https://developer.mozilla.org/en-US/docs/Web/CSS/Scaling_of_SVG_backgrounds) - This helped me to center and full size the svg pattern on the background. I look forward to learning more about svgs.


## Author

- Frontend Mentor - [@Cpuening84169482](https://www.frontendmentor.io/profile/Cpuening84169482)

