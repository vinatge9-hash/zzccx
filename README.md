# Brew & Beans - Coffee Shop Website

This repository contains a complete, production-ready five-page coffee shop website built with Tailwind CSS via CDN. The site follows the provided design system guidelines, uses a coffee-themed color palette, and includes placeholder image tokens for dynamic image rendering.

Files
- index.html: Home landing page with hero section, features, and store info.
- menu.html: Menu page featuring drinks and pastries.
- gallery.html: Gallery page showcasing photos of the space and offerings.
- about.html: About page with the brand story and team notes.
- contact.html: Contact form and store information.
- README.md: This documentation file.

Fonts
- Headings use Montserrat; body text uses Open Sans (as per coffee shop category guidelines).
- Fonts are loaded from Google Fonts via standard <link> tags in the head.

Accessibility & Semantics
- All pages use semantic HTML5 elements: header, nav, main, section, article, footer.
- All images use descriptive alt attributes.
- 100% Tailwind CSS utility classes for styling (no external CSS files).

Image Placeholders
- All images are referenced via the placeholder syntax: https://pixabay.com/get/gfd1cd123a08a5e316fa121a6c6bd8002bb2d04be2aa4257dc2c43f746c3184fe1b8d5a11419b18855c2a5b1ec1eb155c184737b27c9b9d2fd3544caeca8c9d54_640.jpg. Example: <img src='https://images.pexels.com/photos/32946099/pexels-photo-32946099.jpeg?auto=compress&cs=tinysrgb&h=650&w=940' alt='Cozy coffee shop interior'>.

How to Run
- Open any HTML file in a browser. The site uses Tailwind via CDN for styling.
- No backend is required for this static mockup. You can replace image placeholders with real URLs as needed.

Notes
- For production deployment, you might replace the Tailwind CDN with a build pipeline (PostCSS + Tailwind) for optimal performance and offline usage.
