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

## Overview

### The challenge

Build out the project this profile card component and get it looking as close to the design as possible with the designs provided.

![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg)

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

### Screenshot

Here's the finished project.

![Finished project screenshot](./screenshot/screenshot-finished-project.png)

### Links

- Repository URL: [https://github.com/o0oDanielHaroo0o/profile-card-component](https://github.com/o0oDanielHaroo0o/profile-card-component)
- Live Site URL: [https://o0odanielharoo0o.github.io/profile-card-component/](https://o0odanielharoo0o.github.io/profile-card-component/)

## My process

- I started by analyzing the image of the original design and planning my approach.
- I created the basic HTML structure and gave classes to the elements.
- I positioned the card container using the property position absolute and negative margins.
- I positioned the user info and the stats inside the card using box-model properties.
- I styled the elements that I had already positioned inside the card container.
- I positioned the profile picture with position absolute and styled it.
- I adjusted the previous styles to look better and closer to the original design.
- I styled the card container with a border radius and a box-shadow to look as close as possible to the original design.
- I finished by positioning and styling the attribution section on the bottom of the page.

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

My goal with this project was to improve my understanding of the position properties. Before this project I was relying on Flexbox to position almost everything. I managed to reach my goal, now I feel more confortable using this properties.

One thing I found challenging was trying to center the card vertically, I had to google how to do it without using flexbox. I quickly found the solution and I'll definitely will use this method again when I need it:

```css
.card {
  position: absolute;
  top: 50%;
  height: 400px;
  margin-top: -200px;
}
```

I also would like to highlight this code that I thought of:

```css
.stat-container {
  display: inline-block;
  width: 31.55%;
  height: 100%;
  padding: 28px 0;
  text-align: center;
}
```

I wanted to position three divs next to each other withouth using flexbox (which was the challenge I set for myself) or float. This way I also managed to use the same class and code for all three divs.

### Continued development

- I would like to keep sharpening my understanding of the position properties.
- I would like to get better at trying to copy box-shadows, I found it quite challenging but I got as close as I could.
- I want to learn more about responsive design, I currently don't know much about it, only what I can intuit.
- I also want to learn better ways to write css without repeating myself so much, I did the best I could with my current knowleadge.

### Useful resources

- [Center div](https://www.freecodecamp.org/espanol/news/centrar-en-html-div-con-css/) - This helped me center the card using position instead of flexbox. (The page is in spanish)

## Author

- Frontend Mentor - [@o0oDanielHaroo0o](https://www.frontendmentor.io/profile/o0oDanielHaroo0o)
- GitHub - [o0oDanielHaroo0o](https://github.com/o0oDanielHaroo0o)
