# ✏️Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📄Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

---

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### 📷Screenshot

![Captura](./Captures/Desktop%20design.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/kiddhermez/Product-preview-card-component.git)
- Live Site URL: [Add live site URL here](https://splendorous-frangollo-8800d5.netlify.app/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### 🎓What I learned

The first learn that I get was the use of flex-box with his properties like:

```css
.info {
  padding: 25px;
  width: 350px;
  display: flex;
  flex-flow: column wrap;
  justify-content: space-between;
}
```

with this project I also learn the use of media querys:

```css
@media (max-width: 425px) {
  body {
    padding: 10px;
  }
  .container {
    width: 90vw;
    height: 100vh;
    flex-wrap: wrap;
  }

  .image {
    background-image: url("/images/image-product-mobile.jpg");
    background-repeat: no-repeat;
    border-radius: 10px 10px 0 0;
  }
}
```

## 👻Author

- Frontend Mentor - [@kiddhermez](https://www.frontendmentor.io/profile/kiddhermez)
