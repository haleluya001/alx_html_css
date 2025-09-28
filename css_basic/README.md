# CSS Basic Project

## Overview

This project demonstrates the use of **CSS** to style HTML pages while maintaining a responsive layout. It covers:

- Flexbox layout for a structured and flexible page design
- Mobile-friendly adjustments with responsive media queries
- Custom styling for headers, articles, asides, and footers
- Use of a Unicode logo as a simple branding element

The website includes two HTML pages:

- `index.html` – main portfolio page
- `tweets.html` – secondary page with a similar layout

---

## Repository Structure

alx_html_css/
└── css_basic/
├── index.html
├── tweets.html
├── base.css
└── styles.css



- `base.css` → base styles, resets, and font settings  
- `styles.css` → custom styles including Flexbox layout, mobile responsiveness, colors, and backgrounds  
- `index.html` → main portfolio page with header, article, aside, and footer  
- `tweets.html` → secondary page with a similar layout  

---

## Features

### Flexbox Layout

- The `<body>` is a **column flex container**: header → main → footer  
- The `<main>` section is a **row flex container**: article + aside  
- Article takes **2/3 of width**, aside takes **1/3**  
- Allows content to resize and adjust automatically  

### Responsive Design

- Add `class="works_on_smartphone"` to `<body>` for mobile-friendly layout  
- Media queries stack `<article>` and `<aside>` vertically on small screens  
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ensures proper scaling on smartphones  

### Customization

- Header includes a Unicode logo: 🎓 (graduation cap)  
- Custom colors, backgrounds, borders, and text styles applied in `styles.css`  
- The content inside `<article>` and `<aside>` can be freely customized without breaking layout  

---

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/haleluya001/alx_html_css.git
