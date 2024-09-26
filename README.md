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

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Github](https://github.com/hugopfe/blog-preview-card/tree/main)
- Live Site URL: [Github Pages](https://hugopfe.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I have learned more to reuse values in many CSS properties to unify spaces, font sizes, and colors.

```css
:root {
    --color-1: #F4D04E;
    --color-2: #6B6B6B;
    --color-3: #111111;

    --spacing-1: 4px;
    --spacing-2: 12px;
    --spacing-3: 16px;
    --spacing-4: 24px;

    --text-size-1: 0.875rem;
    --text-size-2: 1rem;
    --text-size-3: 1.5rem;
}
```


```css
.category {
    ...
    padding: var(--spacing-1) var(--spacing-2);

    font-size: var(--text-size-1);
    ...
    
}

.publish-date {
    font-size: var(--text-size-1);
}
```

## Author

- Github - [HugoPFe](https://www.your-site.comhttps://github.com/hugopfe/)
- Frontend Mentor - [@hugopfe](https://www.frontendmentor.io/profile/hugopfe)
