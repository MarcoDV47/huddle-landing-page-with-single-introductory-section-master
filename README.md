# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Giving it another go](#giving-it-another-go)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

![Screenshot of the challenge](./design/desktop-design.jpg/)

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

### Giving it another go

I really enjoyed to tackle this challenge again, because I felt that I have improved a lot. I switched from FLEX to GRID and it was a good decision. Many problems I had were fixed in a much faster and easy way.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- ~~Flexbox~~
- GRID

#### Planning

##### Old Version

![Old-planning-screenshot](./report/old-layout(FLEX).png/)
First i took a screenshot to understand the layout and decided to go with flex (maybe grid was better).
I really struggled with this one and it's still far from perfect, but i decided to give it a go some other time.

##### New Version

![New-planning-screenshot](./report/grid.png)
Using grid was way easier to construct this layout.

### What I learned

#### Box-shadow

I found out how to make shadows that look good using this code

```css
.proud-of-this-css {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}
```

from: <https://www.w3schools.com/css/css3_shadows_box.asp>

### Continued development

#### ~~Background-image~~ FIXED

The background image was smaller than the div, i tried using

```css
background-size: cover;
```

but it's still broken

![gif of the shrinking layout showing the bugged backgroung image](./report/Background.gif/)

##### ~~Attribution~~ REMOVED ATTRIBUTION

![Screenshoot of the attribution text placed in the middle of the page](./report/atribuicoes.png/)

The p element was in the middle of the screen, and i don't know how to solve it
My solution was to put the footer element inside the section of my code, it kinda solved the problem but there must be a better way

### Useful resources

- [W3Schools](https://www.w3schools.com/css/css3_shadows_box.asp) - This helped me using box-shadow. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@MarcoDV47](https://www.frontendmentor.io/profile/MarcoDV47).
[EOF]
