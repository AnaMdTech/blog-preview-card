# Frontend Mentor - Blog Preview Card Solution

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Blog Preview Card Screenshot](./screenshot.png)

### Links

- **Solution URL**: [GitHub Repository](https://github.com/AnaMdTech/blog-preview-card.git)
- **Live Site URL**: [Live Demo](https://blog-preview-card-ana-md.netlify.app/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I Learned

This project reinforced several key web development concepts:

1. **Clean HTML Structure**  
   I emphasized semantic HTML to ensure accessibility and maintain a well-structured page for the blog preview card.

2. **CSS Styling**  
   Leveraged Flexbox for layout and responsiveness, ensuring a seamless experience across various screen sizes.

3. **Accessibility**  
   Incorporated best practices like semantic elements and alt attributes for images to improve accessibility.

4. **Hover Animations**  
   Added hover effects to the card title for improved interactivity.

5. **Box Shadows**  
   Enhanced the card's visual appeal by applying a subtle box shadow.

6. **Font Integration**  
   Learned a new method of font inclusion using link elements for easy implementation.

#### Example Code Snippets

Here is an example of my card's HTML structure:

```html
<div class="blog-card-container">
  <div class="card">
    <img
      src="assets/images/illustration-article.svg"
      alt="Illustration of an article"
      class="image-article"
    />
    <div class="card-content">
      <span class="tag">Learning</span>
      <p class="date">Published 21 Dec 2023</p>
      <h2 class="title">HTML & CSS Foundations</h2>
      <p class="description">
        These languages are the backbone of every website, defining structure,
        content, and presentation.
      </p>
      <div class="author">
        <img
          src="assets/images/image-avatar.webp"
          alt="Author avatar"
          class="author-avatar"
        />
        <div class="author-name">
          <h3>Greg Hooper</h3>
        </div>
      </div>
    </div>
  </div>
</div>
```

```css
body {
  font-family: "Figtree", sans-serif;
  background-color: hsl(47, 88%, 63%);
  display: flex;
  flex-direction: column;
  row-gap: 30px;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.blog-card-container {
  background-color: hsl(0, 0%, 100%);
  padding: 20px;
  border-radius: 10px;
  border: 1px solid #000;
  box-shadow: 10px 10px 0px hsl(0, 0%, 0%);
  max-width: 400px;
  margin: 0 auto;
}

.image-article {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 20px;
}

.tag {
  background-color: hsl(47, 88%, 63%);
  font-weight: 700;
  padding: 5px 10px;
  border: none;
  border-radius: 5px;
  margin-bottom: 5px;
  display: inline-block;
  color: hsl(0, 0%, 7%);
}

.date {
  font-size: 13px;
  margin-bottom: 10px;
  font-weight: 500;
}

.title {
  font-weight: 700;
  margin-bottom: 10px;
  cursor: pointer;
}

.title:hover {
  color: hsl(47, 88%, 63%);
}

.description {
  font-size: 13px;
  margin-bottom: 10px;
  color: hsl(0, 0%, 42%);
  font-weight: 500;
}

.author {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.author-avatar {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  margin-right: 10px;
}

.author-name {
  font-weight: 700;
  font-size: 13px;
  color: hsl(0, 0%, 7%);
}
```

### Continued development

I plan to focus on improving my CSS skills, especially regarding animations and transitions.

### Useful resources

- [Frontend Mentor QR Code Challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) - The challenge itself was instrumental in enhancing my front-end skills.
- [CSS-Tricks](https://css-tricks.com/) - A fantastic resource for learning CSS

## Author

- Website - [Ana Md](https://github.com/AnaMdTech/)
- Frontend Mentor - [@Ana Md](https://www.frontendmentor.io/profile/AnaMdTech)

## Acknowledgments

Special thanks to Frontend Mentor for providing this challenge and offering a platform to help improve my skills. Also, thanks to the online communities and documentation that provided invaluable insights while building this solution.
