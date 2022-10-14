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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot for desktop](/design/Screenshot_7.png)

![Screenshot for desktop](/design/Screenshot_8.png)

![Screenshot for mobile](/design/Screenshot_9.png)

### Links

- Solution URL: [solution URL here](https://github.com/abdullah43577/nft-preview-card)
- Live Site URL: [live site URL here](https://nftcardpreviewz.netlify.app/)

## My process

Desktop-first workflow

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

Just glancing through this code, after I've finished writing the code, it felt so easy. but honestly, the hardest part for me was the aspect where on hover, we were to render another image on top of the previous image and with background colour as well with the opacity of the background lighter than the image itself being rendered alongside. I've never done any project as such. So having coded this today I learnt how to do just that. Some of the code snippets were the codes are:

```css
.imgCont {
  width: 100%;
  display: flex;
  justify-content: center;
}

.imgCont img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 20px;
  transition: all 1s ease-in-out;
}

div.viewImageContainer {
  position: relative;
}

div.viewcontainer {
  position: absolute;
  top: 0px;
  left: 0px;
}

div.viewcontainer img {
  opacity: 0;
  padding: 110px;
  color: white;
}

div.viewcontainer img:hover {
  opacity: 1;
  cursor: pointer;
  background-color: rgba(0, 255, 247, 0.3);
  transition: all 0.5s ease-in-out;
}
```

### Useful resources

- [MDN CSS Resource](https://developer.mozilla.org/en-US/docs/Learn/CSS/Howto/Make_box_transparent#:~:text=Changing%20the%20opacity%20of%20the%20background%20color%20only,-In%20many%20cases&text=To%20achieve%20this%2C%20use%20a,background%20color%20to%2050%25%20opacity.) - This helped me for reducing opacity of a backgroundColor without affecting the child elements. I really liked this pattern and will use it going forward.

## Author

- Website - [Abdullah Ayoola](https://github.com/abdullah43577/nft-preview-card)
- Frontend Mentor - [@abdullah43577](https://www.frontendmentor.io/profile/abdullah43577)
- Twitter - [@officialayo540](https://twitter.com/officialayo540)
