# Week 02: CSS Mastery

## Author
- **Name:** Trevor Wachira
- **GitHub:** [@TrevorWachira690](https://github.com/TrevorWachira690)
- **Date:** June 26, 2026

## Project Description
This week I styled my Week 1 portfolio using CSS. I learned the box model, typography, colors, Flexbox, CSS Grid, and mobile-first responsive design. The result is a portfolio that looks good on phones, tablets, and desktops.

## Technologies Used
- HTML5
- CSS3
- Google Fonts (Poppins & Open Sans)
- CSS Custom Properties (variables)
- Flexbox
- CSS Grid
- Media Queries
- Git
- GitHub Pages

## Features
- External `styles.css` linked to all portfolio pages
- Typography system with CSS variables (`--font-xs` through `--font-4xl`)
- Color palette with CSS variables (primary, secondary, background, text, muted)
- Box model practice page with content, padding, border, and margin examples
- Flexbox practice page (navigation bar, card row, footer layout)
- CSS Grid practice page (photo gallery, magazine layout, responsive project grid)
- Mobile-first responsive design with breakpoints at 768px, 1024px, and 1280px
- CSS-only hamburger menu on mobile; horizontal nav on desktop
- Responsive project grid (1 column mobile, 2 tablet, 3 desktop)
- Contact page with form + sidebar layout on larger screens
- Hover, focus, and transition effects on buttons, links, and cards

## How to Run
1. Clone this repository
2. Open `index.html` in your browser
   OR
   Run `npm install` then `npm start`

## Lessons Learned
I learned that CSS is not just about colors — it is about how every element sits on the page. The box model taught me why padding and width calculations matter. Flexbox made navigation and card rows much easier to align. CSS Grid gave me precise control over gallery and magazine-style layouts. Mobile-first design helped me build for small screens first, then add styles for larger screens.

## Challenges Faced
1. **Box model width bug** — My card was 340px instead of 300px because padding was added on top of the width. I fixed it with `box-sizing: border-box`.
2. **Mobile navigation** — I struggled with hiding and showing the menu on small screens. I solved it with a CSS-only checkbox toggle (no JavaScript needed).
3. **Responsive grid** — Getting the project cards to show 1, 2, or 3 columns at different screen sizes took practice with media queries and `grid-template-columns`.

## Screenshots
![Styled portfolio homepage](https://github.com/TrevorWachira690/iyf-s11-week-01-TrevorWachira690/blob/main/images/redesigned-website.png)

## Live Demo
[View Live Demo](https://trevorwachira690.github.io/iyf-s11-week-02-TrevorWachira690/index.html)

## Practice Files
| File | Task |
|------|------|
| `box-model-practice.html` | Task 3.2 — Box Model |
| `flexbox-practice.html` | Task 4.1 — Flexbox Layout |
| `grid-practice.html` | Task 4.2 — CSS Grid Layout |
