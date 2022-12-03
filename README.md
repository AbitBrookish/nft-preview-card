# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

1. [Mobile](./screenshots/Mobile-finish.png)
2. [Desktop](./screenshots/Desktop-finish.png)

### Links

- Solution URL: [solution URL](https://github.com/AbitBrookish/nft-preview-card)
- Live Site URL: [live site](https://abitbrookish.github.io/nft-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mozilla DevTools


### What I learned

I found that I had to revisit hover effects and overlays, as there were some things I had forgotten and (unsurprisingly) some things I didn't know. Such as: use of opacity, transition integration, and using color alphas. Here is an example pulled from the stylesheet:

```css
.overlay {
  position: absolute;
  display: grid;
  place-content: center;
  width: 100%;
  height: 283px;
  border-radius: 8px;
  background-color: hsla(178, 100%, 50%, 50%);
  opacity: 0;
  transition: all .5s ease;
}

.overlay:hover {
  opacity: 1;
  cursor: pointer;
}
```

### Continued development

During the project, as I delved deeper into hover and active effects, I say that there was a section of learning related to hover and active-- ::before and ::after. I'll be focusing on that aspect of css for the next while. 

### Useful resources

- [W3schools](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - Used this resource to get a better grasp on image overlay as it related to ::hover. 
- [Kevin Powells Youtube](https://www.youtube.com/@KevinPowell) - One of my go-to people on youtube for html5 and css3 tips and tutorials. He had a particular video on ::before::after and ::hover overlays.


## Author

- Website - [AbitBrookish Github](https://github.com/abitbrookish)
- Frontend Mentor - [@AbitBrookish](https://www.frontendmentor.io/profile/abitbrookish)


## Acknowledgments

I want to give a shoutout to my wife, who saw me starting to get frustrated about a small problem, and reminded me that between my project and fact-finding, I hadn't taken a break. At which point I took a break, and came back refreshed. 

Also to Kevin Powell for reminding me that as an (aspiring) web developer, taking a design and taking it from top to bottom, step-by-step is the best course of action when coding; turn your big problems into smaller problems, and solve the small problems. 
