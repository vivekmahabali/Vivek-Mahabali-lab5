# WanderNest Travels

**Capstone Project: Travel Agency Website (Lab Assignment 5)**
**Name:** Vivek Mahabali
**Roll No.:** 2601730115
**University:** K.R. Mangalam University

## About
A responsive single-page website for a fictional travel agency, built with HTML5 and CSS3 only (no JavaScript, no frameworks).

**Theme:** Travel Agency Website

## Sections
- Header with logo, navigation and skip link
- Hero banner with tagline and button
- Popular destinations, tour packages and offer banners
- How It Works steps and itinerary table
- Testimonials and travel blog (expandable tips)
- Enquiry form
- Footer with contact links, SVG social icons and copyright

## Breakpoints and layout
- 1440px and above: slightly larger root font size
- 1024px and below: two-column grids
- 768px and below: single-column grids, stacked header and banners
- 480px and below: compact navigation, single-column form

Flexbox handles the header, footer, hero, cards and banners. CSS Grid handles card layouts and the form. Colours, font and shared spacing use CSS variables.

## Requirements covered
| Requirement | Where |
|---|---|
| Semantic HTML5 | header, nav, main, section, article, aside, figure, footer |
| Flexbox | header, navigation, hero, cards, offer banners |
| CSS Grid | destinations, packages, steps, reviews, blog, form |
| Responsive design | media queries at 1440px, 1024px, 768px and 480px |
| Animation | hero fade and slide keyframes |
| Lists | navigation, destinations, steps, footer |
| Hover effects | navigation, buttons, cards, table rows |
| Form validation | required, email type, 10-digit pattern, min/max |
| Accessibility | alt text, labels, table scope, visible focus, reduced motion |

## How to run
Unzip the folder and open `index.html` in a browser. The Montserrat font needs internet access; otherwise a system font is used.

GitHub Pages link: not published yet.

## Screenshots
![Desktop](screenshot-desktop.png)
![Mobile](screenshot-mobile.png)

## Structure
    index.html
    style.css
    images/
    screenshot-desktop.png
    screenshot-mobile.png
    README.md

## Notes
The agency, prices, offers and reviews are made-up sample content. Images are SVG illustrations. The form is a front-end demo and does not store or send data.
