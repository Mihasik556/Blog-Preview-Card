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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/screenshot.png)

### Links

- Solution URL: [](https://github.com/Mihasik556/Blog-Preview-Card)
- Live Site URL: [](https://mihasik556.github.io/Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

There are some parts of my code that I`m really proud of.

For example, I like how I used 'figure' tag for better semantics:

```html
<figure class="image"></figure>
```

and

```html
<figure>
    <img
        class="author-avatar"
        src="assets/images/image-avatar.webp"
        alt="Article`s author avatar with smilinig man on it"
    />
</figure>
```

Also I`m very proud of how I managed to make smooth transitions between different sizes.
For example:

```css
.label {
    transition: max-width 0.35s ease;
    transition: min-height 0.35s ease;
}
```

### Continued development

After this project I will continue practicing on Mobile-First Workflow, adaptive CSS sizing and working with Media Queries.

## Author

- Frontend Mentor - [@Mihasik556](https://www.frontendmentor.io/profile/Mihasik556)
