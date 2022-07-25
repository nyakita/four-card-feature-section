# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Links

- Solution URL: [https://github.com/nyakita/four-card-feature-section)
- Live Site URL: [https://four-card-feature-section-sooty-eta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

During this project I learnt how:
1. How to fix ‘fatal: remote origin already exists’ Git error
	git remote - v - to check to which url your origin assigned
	git remote remove origin - to remove everything that is assigned.
2. I learnt how to center div element inside my body by using css:
	margin: 0 auto;
	width:some units
It's important to add some width, otherwise the margin property will not work because there is no relative width towards which we can have margins
3. I understood the most important part of building the web-page is to built a layout of divs, then try to work on the design and other things.
4. Also I discovered very powerful tool as grid. This feature helped me to build the page I would like to see.

To see how you can add code snippets, see below:

```html
<header class="item item-1">
    <h1><span>Reliable, efficient delivery</span> <br>
      Powered by Technology</h1>

    <p>Our Artificial Intelligence powered tools use millions of project data</p>
    <p>points to ensure that your project is successful</p>
  </header>

      <div class="item item-2">
        <h2>Supervisor</h2>
        <p>Monitors activity to identify project roadblocks</p>
        <img src="images/icon-supervisor.svg" alt="supervisor-image" class="image">
      </div>
      <div class="item item-3">

          <h2>Team Builder</h2>
          <p>Scans our talent network to create the optimal team for your project</p>
          <img src="images/icon-team-builder.svg" alt="team_builder_image" class="image">
      </div>
      <div class="item item-4">
        <h2>Karma</h2>
        <p>Regularly evaluates our talent to ensure quality</p>
        <img src="images/icon-karma.svg" alt="karma-image" class="image">
      </div>

      <div class="item item-5">
        <h2>Calculator</h2>
        <p>Uses data from past projects to provide better delivery estimates</p>
        <img src="images/icon-calculator.svg" alt="calculator_image" class="image">
      </div>
```
```css
.container{
  display: grid;
  width:1440px;
  height:100vh;
  grid-template-columns: .9fr .9fr .9fr;
  grid-template-rows:  1.2fr 1.2fr 1.2fr 1.2fr 1.2fr;
  grid-template-areas:
  "item-1 item-1 item-1"
  ". item-3. "
  "item-2 . item-5"
  ". item-4 . "
  "item-6 item-6 item-6"
}
```
### Continued development

### Useful resources

- https://www.youtube.com/watch?v=ojKbYz0iKQE - It helped me to understand what is grid and how to use it in the project. It's clearly explained and there was an example of the concept.


## Author
- Frontend Mentor - [@nyakita](https://www.frontendmentor.io/profile/nyakita)

## Acknowledgments

I would to thank my wift for help and support during this project, thanks to her eyes I would choose the right font-size and color for this font as well.

