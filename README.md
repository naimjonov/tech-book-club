# Frontend Mentor - Tech book club landing page solution

This is a solution to the [Tech book club landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview
I created a responsive landing page for a book club using pure HTML and CSS! The layout was based on a Figma file and tried my best to make the layout changes as seamless as possible. I'm pretty new to responsive layouts though so it's not perfect.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
Originally I started with the desktop version first and tried adjusting my layout to size down, but has major difficulties trying to adjust my code for smaller screens. I saw a recommendation online that it may be easier to start with mobile first as it may be easier to add rather than remove or omit styles. With this in mind, I made a frustrating but probably needed decision to scrap my last attempt and start a new one. So you're actually looking at my SECOND attempt at this challenge! While part of it could be that I've already attempted this challenge once so some parts were not as difficult, but I ended up finishing this project within 2.5 days rather than my first attempt which took 5 days.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned that the best approach for myself is to start with mobile-first! It was definitely easier to add styles when bigger screens permitted, than to remove styles when the layout got smaller.

While I understand that CSS is probably more forgiving and easier to work with when it comes to making seamless layouts, especially when part of a design utilizes cards, I've always found Flexbox easier to understand. Since I only did this project with HTML and CSS, I was not sure if there was a way for me to remove the "journey steps" of the design for smaller screens. Therefore, I decided to just keep this part of the design even for the tablet and mobile versions. In this part, I utilized CSS Grid, albeit a very small portion of my style rules, but it was nice getting a change and challenging myself. I was also proud when I realized that in a design aspect, CSS grid would be a better option since I could make the layout have 2 cards per row when the screen gets smaller.

I also learned that you can create a type of border using nested box-shadows! While first attempting the :hover elements for the buttons, I thought I needed to change the border itself to be a double border instead of a single border. Upon looking at the Figma file though, I saw that the design actually utilized two box shadows to create the border effect. It was frustrating at first because I did not realize that you could nest box-shadow effects on a single style rule, but all you needed to two was add the two box-shadow effects on the single style rule, separated by commas!

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

The transition between the screen sizes on the figma file are nowhere near perfect... but since I'm new to responsive layouts, I figured this was a good-enough effort to showcase my first attempt. :D I think something I could work on in the future is add one more media query between each screen size (e.g., I would add another media query inbetween 375px and 768px, and then one more between 768px and 1454px). Also, I'm only used to coding myself based on pixels, I would like to start getting used to using rem since that is more relative to the users screen-size. That is something I probably plan on doing the next time I create a landing page or a full blown website.
