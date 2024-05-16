# Social-links

# Frontend Mentor - Recipe page solution

This is my personal solution to the [Social links challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ/hub). Frontend Mentor challenges help you improve your coding skills by building realistic projects and I enjoyed working on this project.

## Table of Contents

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

### Screenshot

#### Desktop view
![](/images/screencapture-ckola99-github-io-Social-links-2024-05-14-16_20_34.png)

#### Mobile view
![](/images/screencapture-ckola99-github-io-Social-links-2024-05-14-16_23_58-mobile.png)

### Links

- Live Site URL: [Live site URL here](https://ckola99.github.io/Social-links/#)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I did not necessarily learn much in this project but I reinforced my knowledge on css flexbox and used how to use flex grow property in a practical manner.

```css

.links {
	display: flex;
	flex-direction: column;
	width: 100%;
	font-size: 0.85rem;
	font-weight: 600;
	list-style-type: none;
	padding: 0;
}

.links li {
	margin: 5px;
	flex: 1;
}

.links a {
	display: block;
	background-color: var(--grey);
	border-radius: 0.5rem;
	padding: 8px;
	text-align: center;
	color: var(--white);
	text-decoration: none;
}


```

### Continued development

The areas where I think I'd like to improve is my understanding of positioning of elements in css. I want to be able to make the right decisions when placing elements whether it be with CSS grid or flexbox. My ability to apply pre-existing knowledge and using the docs appropriately.

### Useful resources

- [Css reset](https://www.joshwcomeau.com/css/custom-css-reset/) - this article taught me about CSS reset and a little bit more about css defaults.
- [MDN](https://developer.mozilla.org/en-US/) - this website is what I used to make sure I used the correct selectors and available properties.
- [ChatGPT](https://chatgpt.com) - I used chatgpt for small queries about my code where I couldn't necessarily see issues.

### Author

- Website (yet to be created)
- Frontend Mentor [@CKola99](https://www.frontendmentor.io/profile/Ckola99)

### Acknowledgements

I learned a bit from [Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/).
