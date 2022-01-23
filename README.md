# Frontend Mentor - Testimonials grid section solution

This is a solution to the
[Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).
Frontend Mentor challenges help you improve your coding skills by building
realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections
you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/images/screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://testimonial-grid-section-favvie.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I refreshed my knowledge on css grid. The grid-template-column grid-auto-rows :
using minmax helps to set a min height and using auto as the second argument
allows the row to expand if its content has a height that is greater than 100px
column-gap row-gap grip-gap grid-row grid-column the use of fr compared to % :
using % could lead to width and margin issues the use of repeat justify-items:
start, end, stretch, center align-items: start, end, stretch, center

Use this section to recap over some of your major learnings while working
through this project. Writing these out and providing code samples of areas you
want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
.proud-of-this-css {
	color: papayawhip;
	grid-template: 1fr 2fr;
	grid-auto-rows: minmax(100px, auto);
	grid-column: 1/3;
	/* it starts from the first column and ends at the third */
	grid-row: 1/3;
	/* same principle */
}
```

### Continued development

I did not utilize the grid-gap, justify-items among others in this project.
Hopefully, in the next.

### Useful resources

- [Brad Traversy crash course on CSS Grid](https://www.youtube.com/watch?v=jV8B24rSN5o) -
  This helped me for refresh my knowledge on CSS Grid. I really liked his
  explanation and will use it going forward.

## Author

- Frontend Mentor - [@favvie](https://www.frontendmentor.io/profile/favvie)
- Twitter - [@\__kenpachi_](https://www.twitter.com/__kenpachi_)
