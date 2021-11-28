# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Build out the project to the designs provided (including the page background).

### Screenshot

![](./design/my-solution.png)

### Links

- Solution URL: [GitHub](https://github.com/marisudris/frontend-mentor-profile-card-component)
- Live Site URL: [GitHub Pages](https://marisudris.github.io/frontend-mentor-profile-card-component/)

## My process

As always - first I came up with a solid enough HTML structure that's both semantic and provides styling hooks.  
Next I did the page background which required some tweaking and extra knowledge on background positioning for responsive viewports.  
Then I worked on the card using the top-down approach - _big_ things first, *smaller* details later.
I styled and positioned the profile image, then the bio information (using flex) and similarly with stats section (again - using flex twice).  
Afterwards I noticed the card in design has a `box-shadow` so I tried to make it as close to the design as possible, without
overthinking and spending too much time on it.  
In the end I tweaked the spacing and font-sizes as a finishing touch.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Background images and color can be a bit tricky when element's background is composed of multiple elements (two gradient circle images in my case).
Getting them to act properly when the viewport size changes required a bit of research and patience.
I found out that the `background-postition` can act differently when the viewport changes - depending on the side with relative to which the background position is declared  - and behavior that makes sense, however I never really encountered a case where that really mattered to me - until this project.

### Continued development

Going forward it would be worth spending some time on things everyone does but rarely does in-depth research
on - like borders, backgrounds and their shorthands.

### Useful resources

- [Backgrounds on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/background) - if you want to recap on backgrounds, how their shorthands work, how to specify multiple background images, how they relate to background color, how their positioning works etc.

## Author

- Frontend Mentor - [@marisudris](https://www.frontendmentor.io/profile/marisudris)
- GitHub - [@marisudris](https://www.github.com/marisudris)
