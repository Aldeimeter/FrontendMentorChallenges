# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)
![](./mobile-screenshot.png)

### Links

- Solution URL: [Click](https://github.com/Aldeimeter/FrontendMentorChallenges)
- Live Site URL: [Click](https://aldeimeter.github.io/FrontendMentorChallenges/social-links-profile-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
.links li {
  font-weight: 700;
  background: var(--grey-700);
  width: 100%;
  border-radius: 7px;
}
.links a {
  display: block;
  border-radius: 7px;
  padding: 10px;
  width: 100%;
  text-decoration: none;
  color: var(--white);
}
.links a:hover,
.links a:focus {
  color: var(--grey-800);
  background: var(--green);
  cursor: pointer;
}
```

Not sure if it is the best way of implementing this, but it works.
(Change colors of whole container content on both hover and focus)
