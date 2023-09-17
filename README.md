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

## Overview

This is a responsive card component built with HTML & CSS.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [GitHub Repo](https://github.com/kwekuduahh/nft-card-component)
- Live Site URL: [NFT Card Component Live](https://nft-asset-card-component.netlify.app/)

## My process

1. I gathered the design assets on my Figma board.
2. Designed the interface on Figma.
3. Proceeded to initialize a git repo and connect the repo.
4. I created a working branch to ensure that changes are well tracked and prevent errors from the main branch.
5. Then, I started writing the code to the working branch.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Clamp

### What I learned

I learnt how to make good use of css flexbox and clamp() to make responsive layouts.

To see how you can add code snippets, see below:

```html
<div class="image-overlay">
	<img
		src="images/icon-view.svg"
		alt="icon-view"
	/>
</div>
```

```css
.image-overlay {
	position: absolute;
	opacity: 0;
	background-color: var(--Cyan);
	width: clamp(304px, 90%, 314px);
	height: clamp(304px, 90%, 314px);
	border-radius: 10px;
	transform: translate(0%, -100%);
	transition: 0.5s ease;
	display: flex;
	justify-content: center;
	align-items: center;
}
```

```js
const proudOfThisFunc = () => {
	console.log('🎉');
};
```

### Continued development

I will keep exploring creating responsive and reusable code in future projects.

### Useful resources

- [MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS) - This helped me with css clamp() and the hover effect on the image.

## Author

- Website - [Design Portfolio](https://kweku-asamoah.webflow.io)
- Frontend Mentor - [@kwekuduahh](https://www.frontendmentor.io/profile/kwekuduahh)
- Twitter - [@kwekuduahh](https://www.twitter.com/kwekuduahh)
