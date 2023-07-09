# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshots
![Desktop](assets/images/Frontend%20Mentor%20Workit%20landing%20page%20-%20desktop.png)

![Tablets](assets/images/Frontend%20Mentor%20Workit%20landing%20page%20-%20tablet.png)

![Mobile](assets/images/Frontend%20Mentor%20Workit%20landing%20page%20-%20mobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/PRINCEKK122/work-it-landing-page)
- Live Site URL: [Add live site URL here](https://workit-front-end-mentor.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS Display Properties
- Flexbox
- Mobile-first workflow
- Media Queries

### What I learned

The main challenge for this project was cropping parts of the hero section, using CSS clip-path, to be specific ellipse value of the **CSS clip-path**. 

Also, this is the first time that I have used max-width, and max height to position elements that responds to all devices.

To see how you can add code snippets, see below:

```css
.crop {
    clip-path: ellipse(170% 100% at 50% 0);
}

.founder-container {
    position: relative;
    top: 3rem;
    padding: 0 1.6rem;
    width: 100%;
    max-height: 65rem;
    max-width: 80rem;
    margin: 0 auto;
}
```

### Continued development
I will be learning **CSS Grid** next, and I will be using that in future projects, together with **CSS Flexbox** to create more complex and beautiful layouts. I will also be learning **SASS**, and **CSS Custom Properties**, because I found myself doing a lot of repetitions in this project. 

### Useful resources
I am using - [Modern HTML and CSS from the beginning](https://www.udemy.com/course/modern-html-css-from-the-beginning/) - I like his teaching and his project based tutorial.

## Author

- Website - [Prince Awuah Karikari](https://github.com/PRINCEKK122/work-it-landing-page)
- Frontend Mentor - [@PRINCEKK122](https://www.frontendmentor.io/profile/PRINCEKK122)

## Acknowledgments
My friend, **Seth Baffuor Akoto Acheampong** helped me tremendously to read the measurement of figma.