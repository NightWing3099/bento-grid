# Bento Grid

A responsive, bento-style marketing landing page built as a [Frontend Mentor](https://www.frontendmentor.io) challenge. The layout showcases AI-powered social media management features using a modern card grid that adapts smoothly from mobile to desktop.

![Desktop preview of the bento grid page](./bento-desktop.png)

## Features

- **Responsive bento grid layout** – scales cleanly across mobile, tablet, and desktop breakpoints.
- **CSS Grid + Flexbox** – uses `grid-template-columns`, `grid-row/column` placement, and `order` for the mobile re-ordering.
- **Tailwind CSS utility classes** for colors, spacing, typography, and quick responsive tweaks.
- **Custom local fonts** with `@font-face` for DM Sans variable and italic fonts.
- **Accessibility touches** including semantic HTML, descriptive `alt` text, and visible focus states.

## Tech Stack

- HTML5
- CSS3 (custom `styles.css`)
- [Tailwind CSS](https://tailwindcss.com) (via CDN for utility styling)
- DM Sans font family (self-hosted)

## Project Structure

```
├── index.html          # Main markup
├── styles.css          # Custom CSS: fonts, grid, card layout, media queries
├── README.md           # Project documentation
├── design/             # Design reference images
├── assets/
│   ├── fonts/          # DM Sans variable and static font files
│   └── images/         # Illustrations and favicon
└── bento-*.png         # Screenshot previews
```

## What I Practiced

- Building a complex, asymmetrical bento grid that matches a provided design.
- Using CSS `order` to move the left-column desktop cards to the bottom on mobile.
- Combining Tailwind utilities with custom CSS for precise layout control.
- Optimizing typography and spacing with `clamp()` for fluid scaling.

## Author

Coded by [Iree Hale](https://github.com/NightWing3099).

