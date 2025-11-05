## Frontend Mentor - Product Preview Card Component Solution

This is my solution to the Product Preview Card Component Challenge
 on Frontend Mentor.
This project helped me strengthen my HTML and CSS skills, focusing on semantics, accessibility, and responsive design.

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
- See hover and focus states for interactive elements

### Screenshot

![screenshot of my project] (./images/Capturar 3.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here]((http://127.0.0.1:5500/product-preview-card-component-main/index.html))

## My process

### Built with
Semantic HTML5 markup
CSS custom properties
Flexbox
CSS Grid
Mobile-first workflow
Relative units only (rem, em, %, vw, clamp())
Google Fonts: Montserrat and Fraunces

### What I learned

While working on this challenge, I learned to:

Build a semantic and accessible structure using <main> and <article> correctly.

Use CSS custom properties (:root) for consistent colors and typography.

Apply mobile-first responsive design, starting with the small layout and expanding with media queries.

Use relative units (rem, em, vw, clamp) instead of pixels for better scalability.

Implement CSS Grid to create a side-by-side layout for desktop screens.

Adjust image proportions with object-fit: cover and maintain correct border radius between breakpoints.

Use min-height: 100vh and flexbox to center the card vertically and horizontally.

Keep accessibility in mind with descriptive alt text and good color contrast.

Here’s a small example of what I implemented:

<main>
  <article class="product-card">
    <div class="product-image">
      <img src="./images/image-product-desktop.jpg" alt="Gabrielle Essence Eau De Parfum bottle">
    </div>
    <div class="product-details">
      <h2 class="product-category">Perfume</h2>
      <h1 class="product-name">Gabrielle Essence Eau De Parfum</h1>
      <p class="product-description">
        A floral, solar and voluptuous interpretation composed by Olivier Polge, 
        Perfumer-Creator for the House of CHANEL.
      </p>
      <div class="product-pricing">
        <span class="current-price">$149.99</span>
        <span class="original-price">$169.99</span>
      </div>
      <button class="add-to-cart-button">
        <img src="./images/icon-cart.svg" alt="Cart icon">
        Add to Cart
      </button>
    </div>
  </article>
</main>

### Continued development

In future projects, I want to:

Improve my CSS Grid and Flexbox mastery.

Focus more on accessibility testing (e.g., keyboard navigation and ARIA attributes).

Practice design systems and variable naming to keep my code more scalable and readable.

Explore performance and SEO optimization in real projects.

### Useful resources
MDN Web Docs
 – For checking CSS and HTML semantics.

Frontend Mentor Slack Community
 – Great place for feedback and discussions.

Google Fonts
 – For choosing and embedding font families.

## Author
- Frontend Mentor - [@LadyManu](https://www.frontendmentor.io/profile/LadyManu)



