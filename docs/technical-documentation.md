# Technical Documentation

## Project Structure

### index.html
Contains the main structure of the portfolio website:
- Navigation
- About section
- Projects section
- Contact form

### css/styles.css
Responsible for:
- Layout styling
- Responsive design using media queries
- Flexbox navigation layout
- Grid-based project layout

### js/script.js
Handles:
- Smooth scrolling behavior
- Active navigation highlighting while scrolling

---

## Responsive Design Explanation

The website uses:

- **Flexbox** for navigation alignment
- **CSS Grid** for the projects section
- **Media queries**:
  - Below 600px → stacked mobile navigation
  - Above 768px → two-column project grid

This ensures compatibility across desktop, tablet, and mobile devices.

---

## JavaScript Feature Explanation

The script listens to scroll events and:

1. Detects which section is currently visible.
2. Matches the section ID with the navigation link.
3. Adds an "active" class to highlight the current section.

This improves user experience and navigation clarity.