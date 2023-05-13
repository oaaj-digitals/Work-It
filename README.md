# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects, it was used as a project for the Git course I participated with in **Scutigen Community**.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the interface depending on their device's screen size
-   See hover and focus states for all interactive elements on the page

### Screenshot

![Design preview of my solution for the Workit landing page coding challenge](./preview.png)

### Links

-   Solution URL: [https://github.com/oaaj-digitals/Work-It]
-   Live Site URL: [https://oaaj-digitals.github.io/Work-It/]

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Desktop-first workflow
-   Flexbox
-   CSS Grid

### What I learned

With this project I learnt how to better use [Git](https://git-scm.com/) and [GitHub](https://github.com/).

I also learnt how to utilize the **clip-path** properties in css in creating custom design, the code snippet below was used to create the background for the header section

```css
.header-bg {
	width: 100%;
	height: 100%;

	position: absolute;
	top: 0;
	left: 0;
	z-index: -1;

	background-color: var(--primary-color);

	clip-path: ellipse(130% 80% at 50% 0%);
	overflow: hidden;
}
```

### Continued development

-   [ ] Better responsiveness
-   [ ] Convert to React Code

## Author

-   GitHub - [Akintade Japhet](https://github.com/oaaj-digitals)
-   Twitter - [@oaaj_digital](https://www.twitter.com/@oaaj_digital)

## Acknowledgments

I would like to express special thanks to Scutigen community for providing the resources to learn how to better use Git and GitHub and my colleges for their supports throughout the course.
