# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview
![desktop-preview](https://user-images.githubusercontent.com/94350356/182017866-5cd604c2-f1a8-4edd-ad93-d70e28677b12.jpg)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Desktop view:

![2022-07-31 (3)](https://user-images.githubusercontent.com/94350356/182017809-910c61a9-9995-48d1-8228-bc4738f95f6f.png)

Mobile view:

![2022-07-31 (4)](https://user-images.githubusercontent.com/94350356/182017827-e0fe0bdf-1297-4309-acd4-601f974a02c1.png)


### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [Live site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex

### What I learned

This project was very helpfull. I learned to use Z-Index and hover pseudo-elements.

```html
<div class="view">
  <img src="/assets/icon-view.svg" alt="" class="icon-view" />
</div>

<div class="txt">
  <h2 class="hov">Equilibrium #3429</h2>
  <p class="des">Our Equilibrium collection promotes balance and calm</p>
</div>
```

```css
.hov:hover {
  color: var(--hove);
}

.main-img:hover {
  z-index: 0;
}
```

## Author

- Frontend Mentor - [@DEEPAK-tech40](https://github.com/DEEPAK-tech40)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
