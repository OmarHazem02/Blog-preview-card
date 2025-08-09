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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

I built a simple, responsive webpage featuring a blog preview card, designed using only HTML and CSS.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![screen shot of the webpage](webpage-screenshot.png)

### Links

- Live Site URL: https://omarhazem02.github.io/Blog-preview-card/

## My process

 I started by analyzing the provided design and breaking it down into clear sections and individual elements. This made it easier to structure the HTML, assigning descriptive class names to each part for better readability and maintainability.

Once the HTML skeleton was complete, I worked from top to bottom, styling each section step-by-step with CSS until the design matched the challenge requirements.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Through this project, I learned the importance of planning my page structure before starting to code. Breaking the layout into clear sections beforehand made the development process smoother and more efficient.

I also practiced using Flexbox to align elements — for example, positioning the author’s image and name neatly at the bottom of the card. Additionally, I became more comfortable applying the box-sizing: border-box; property to maintain consistent element sizing and simplify layout control.

To see how you can add code snippets, see below:

```html
<div class="author">
  <img src="assets/images/image-avatar.webp" alt="creator image" class="author-img" />
  <p class="author-name">Greg Hooper</p>
</div>

```
```css
.author {
    display: flex;
    gap: 15px;
}
.author-name {
    font-weight: 800;
    align-self: center;
}
/*====================*/
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

```

### Continued development

Strengthen my skills in Flexbox and CSS Grid to build more complex and flexible layouts.

Focus on creating fully responsive designs that work seamlessly across all devices and screen sizes.

Continue practicing and mastering CSS animations and shadow effects to make interfaces more engaging and visually appealing.

### Useful resources

- MDN Web Docs helped me expand my knowledge on certain topics while creating this page..
- Chat gpt Claude supported me as  mentors by helping evaluate and review my code throughout the project.
  
## Author

- Website - [Omar Hazem](https://www.linkedin.com/in/omar-hazem-aa287a273/)
- Twitter - [@Omarhaz67778375](https://x.com/OmarHaz67778375)


## Acknowledgments

I would like to acknowledge AlMadersa, where I am currently studying in the Front-End Development Diploma program.
Special thanks to my course tutor, Mohamed Abu Sarea (محمد أبو سريع), for his valuable guidance and support.

