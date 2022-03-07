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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Looking at the design pic, theres a drop-shadow around the 
<main> div [make flexbox], 
	then inside an img, 
			h1, 
			p, 
			ul [make flexbox] 
				(with two imgs next to text (maybe two smaller flexbox ls elements?)), 
			hr, 
			image + text next to it {flexbox}
Might just be easier to do flexbox within flexbox. Don't think I need the card to flex. it's already small enough to fit on phone screens,
and dont want it to expand to fit desktop. Just need flexbox for positioning.

Other things to consider:
 - semantic html for accessibility
 - CSS presets
 - what units to use. Declare font size in root? (in case user wants to resize font-size for accessibility.)

So a trick I learned in the last QR-code component challenge from reading the Josh Comeau article (listed below) is to use the screenshot function to measure the pixels 
in the design file (first making sure the design file was being displayed as close to the desktop size of 1440px as possible.)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned



If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development
Want to work on using Emmet in VS code to be a little faster.
Maybe try using SASS.

### Useful resources

https://www.joshwcomeau.com/css/pixel-perfection/ - This helped me not stress too much about getting it "pixel perfect" and also taught me the trick of using the screenshot function to get rough sizes from the design.



## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
