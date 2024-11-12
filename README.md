# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%202024-11-12%20193547.png)
![](./images/Screenshot%202024-11-12%20193627.png)

### Links

- Live Site URL: <https://kirlosbasta.github.io/product-preview-card-component-solution>

## My process

I tried mobile first approach, I started by creating the mobile version of the card, then I added the desktop version using media queries.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to make images responsive using the `max-width` property, and how to switch between images using picture element.

```html
<picture>
  <source
    media="(max-width: 500px)"
    srcset="./images/image-product-mobile.jpg"
  />
  <img
    src="./images/image-product-desktop.jpg"
    alt="Perfume"
    class="product-img"
  />
</picture>
```

```css
img {
  max-width: 100%;
}
```

### Useful resources

- [Picture element](https://web.dev/learn/design/picture-element) - This helped me to understand how to switch between images using the picture element.

## Author

- Frontend Mentor - [@kirlosbasta](https://www.frontendmentor.io/profile/kirlosbasta)
- LinkedIn - [kirlos-basta](https://www.linkedin.com/in/kirlos-basta/)
