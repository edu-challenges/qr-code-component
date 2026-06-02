# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). It is a small static page built with semantic HTML and CSS, focused on reproducing the card layout as closely as possible to the provided design.

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
- [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

This project renders a centered QR card with an image, heading, descriptive text, and a footer attribution. The page uses the Outfit font from Google Fonts and a custom color system based on the Frontend Mentor style guide.

### Links

- Solution URL: Not submitted yet
- Live Site URL: Not deployed yet

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first styling
- Google Fonts (Outfit)

### What I learned

While building this component, I practiced choosing semantic elements for a very small page structure. The layout uses `main` for the primary page content, `article` for the card itself, and `footer` for the attribution.

I also reinforced the use of design tokens through CSS custom properties for color, type scale, and font weights.

```html
<main>
  <article>
    <img
      src="./images/image-qr-code.png"
      alt="White QR Code with blue background"
    />
    <div class="text">
      <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </article>
</main>
```

```css
:root {
  --slate-900: #1f314f;
  --slate-500: #68778d;
  --slate-300: #d5e1ef;
  --white: #ffffff;
}
```

### Continued development

In future projects, I want to keep improving in these areas:

- Writing semantic HTML that still makes sense when a component is viewed alone or inside a larger page
- Building responsive layouts with fewer fixed assumptions about viewport width
- Organizing CSS so reusable patterns stay clear as projects grow

### Useful resources

- [Frontend Mentor challenge page](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) - The source of the brief and design goals.
- [Google Fonts - Outfit](https://fonts.google.com/specimen/Outfit) - The font used in the project.
- [MDN Web Docs](https://developer.mozilla.org/) - Helpful reference for semantic HTML elements and general CSS behavior.

## AI Collaboration

I used GitHub Copilot as a support tool while working on the project.

- I used it to discuss semantic HTML choices, especially around when to use `main` with `article` `section` or `div`.
- I used it to review the project files and help turn the starter README template into a project-specific README.

## Author

- GitHub - [Edu Yeves](https://github.com/Yevestevez)
