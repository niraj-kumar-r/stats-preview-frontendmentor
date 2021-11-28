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
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot


![Finished Mobile Site screenshot](design/my-finished-mobile-screenshot.png)
![Finished Desktop Site Screenshot](design/my-Finished-desktop-screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [niraj-stats-preview-card](https://niraj-stats-preview-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- I learnt how to show completely different images, depending upon the device width, using the [picture tag](https://stackoverflow.com/a/50375128).

```css
<h1>Resize Window</h1>
<picture>
  <source srcset="https://via.placeholder.com/1400" media="(min-width: 1400px)"/>
  <source srcset="https://via.placeholder.com/1200" media="(min-width: 1200px)"/>
  <source srcset="https://via.placeholder.com/800" media="(min-width: 800px)"/>
  <source srcset="https://via.placeholder.com/600" media="(min-width: 600px)"/>
  <img src="https://via.placeholder.com/400" alt="example"/>
</picture>
```
- I learnt that a little gap between an img tag and its div container is the intended behaviour, and if we don't want that gap we have to use [diplay: block](https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image) 

- I learnt about [text transforms](https://www.w3schools.com/cssref/pr_text_text-transform.asp) and its use cases.

- I also practically experienced how working with a mobile-first workflow, can make responsive websites easier to make. Since the mobile site is simpler most of the times, I first coded that, and then added complexity on top of that to make the desktop site. 

### Useful resources

- [Stackoverflow](https://stackoverflow.com/) - This really helped me. It has become my go to place for any problem I face, I just google it and this is always the first result and more often than not, it is pretty accurate too, since, someone out there faced the same problem as me and has already asked it here most of the times.

- [W3 schools](https://www.w3schools.com/) - This is an amazing site, which has pretty good explainations, with proper syntax, on most css properties.

- [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - This is the end, all be all of CSS, if you can't find find it here, you haven't looked properly😜.

## Author

<!-- - Website - [Add your name here](https://www.your-site.com) -->
- Frontend Mentor - [@niraj-kumar-r](https://www.frontendmentor.io/profile/niraj-kumar-r)
- Twitter - [@niraj_kumar_r](https://twitter.com/niraj_kumar_r)