# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Static landing page created with HTML and CSS.
- This landing page has been designed to adapt to different screen sizes from smartphones to desktops.
- Use HTML to structure content.
- CSS to apply styles and ensure an optimal user experience on all devices.

### Screenshot

![Huddle landing ](./images/Captura%20de%20pantalla%20.png)

### Links

- Solution URL: [Repository](https://github.com/giohurtado/huddle-landing-page.git)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid
- Mobile-first workflow
- Relative units
- Media queries
- [Fluid type scale calculator](https://utopia.fyi/type/calculator/) - Calculated font sizes
- [Font Awesome](https://fontawesome.com/)
- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Family: [Poppins](https://fonts.google.com/specimen/Poppins)

### What I learned

- Modify the text, images and structure of the page
- Change colors, fonts, sizes and other styles
- Use relative units like em and rem
- Grid and flexbox to create flexible and adaptable layouts

To see how you can add code snippets, see below:

```html
 <article class="landing-header">
        <section class="landing-logo">
          <img src="./images/logo.svg" alt="" class="logo-header" />
        </section>
        <section class="landing-img">
          <img
            src="./images/illustration-mockups.svg"
            alt="illustration-mockups"
          />
        </section>
  </article>
```

```css
.landing {
  display: grid;
  grid-template-rows: repeat(4, max-conent);
  padding: 2.5rem 2rem;
  background: url(./images/bg-mobile.svg), var(--Violet);
  background-repeat: no-repeat;
  background-size: contain;
  background-origin: border-box;
}
```

### Continued development

I would like to continue learning and practicing the concepts of Semantic HTML5, Mobile-first workflow and Media queries.

### Useful resources

- [HTMLreference.io](https://htmlreference.io/) - This helped me for Semantic HTML5. htmlreference.io is a free guide to HTML. It features all elements and attributes.
- [CSSreference.io](https://cssreference.io/) -  It features the most popular properties, and explains them with illustrated and animated examples

## Author

- Frontend Mentor - [@giohurtado](https://github.com/giohurtado)

## Acknowledgments

Research and read documentation, guides and blogs about the technology you want to use for your project.
