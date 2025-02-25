# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Learning grid-template-areas to set complex layouts instead of using spanning

Setting an svg to a bg for certain circumstances

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.testimonials-grid-section {
  display: grid;
  max-width: 20.35rem;
  place-content: center;

  grid-auto-columns: auto;
  grid-template-areas:
    "one"
    "two"
    "three"
    "four"
    "five";
  gap: var(--spacing-24);
}

.testimonial:nth-child(1) {
  grid-area: one;
}
.testimonial:nth-child(2) {
  grid-area: two;
}
.testimonial:nth-child(3) {
  grid-area: three;
}
.testimonial:nth-child(4) {
  grid-area: four;
}
.testimonial:nth-child(5) {
  grid-area: five;
}
```

### Continued development

Might use this more in the future when it comes to creating complex layouts.

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=rg7Fvvl3taU&t=269s) - Kevin powell's
- [Example resource 2](https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts/) - I learned most of my knowledge on responsive layouts on kevin's free CRL course. Personally, i think his teaching style works out really well for me

## Author

- Website - [Add your name here](https://github.com/PastaSus/testimonials-grid-section-main)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/PastaSus)

## Acknowledgments

Learning all of these new things(specifically the grid-template-areas) were all thanks to Kevin Powell's "Learn css grid the easy way" video.
