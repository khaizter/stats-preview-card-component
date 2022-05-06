# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

(./screenshot/result-desktop.png.jpg) - desktop preview
(./screenshot/result-mobile.png.jpg) - mobile preview

### Links

- Solution URL: [Add solution URL here](https://github.com/khaizter/stats-preview-card-component)

## My process

So the first thing that came to my mind is that layout will be a card with a display on top and infos on bottom, that is layout by a flexbox so that i can control it later on media queries to change the flex direction to row reverse to achieve the design on desktop view.

I start by making global styles like putting default styles on global elements and controlling typography and then i make some variables that can help me later in development like colors and font.

Next thing is i make centered div(main-container) and add two div (display/info) in it so the display will contain the image and info contains the text.

I also added the colors, padding, font-sizes etc.

Next is to make the desktop view, i did this part easily because i already planned it out on the start where i just change the flex direction to row reverse and tweak some things like setting the info div to 50%(so that they will equaly half centered just like in preview) and setting text align to left.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Syntactically Awesome Style Sheets](https://sass-lang.com/) - For styles

### What I learned

I applied some of the basic things of sass but i think my organization of scss is kinda messy that is need to improve.
My first approach on the images was to put img and a div in a same spot by using display absolute and that div will have a little transparent so that the image will be seen through
but this approach is kinda cumbersome and take a lot of work to do so i tried to google and find a css property which is mix-blend-mode.

### Continued development

For the next development maybe i will focus more on typography like line-height,font-size,font-weight and margin top and bottom. These things is kinda confusing to me i know how to use it but i'm confused which is control or to change to achieve a certain look. I also want to learn some good practice in handling this type properties base on typography.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/khaizter)
