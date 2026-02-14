# Technical Documentation

## Project Structure

### index.html
Contains the main sections:
- Navigation
- About
- Projects
- Contact form

### css/styles.css
Handles:
- Layout and spacing
- Responsive design using media queries
- Navigation styling using Flexbox
- Projects layout using Grid

### js/script.js
Adds interactivity:
- Smooth scrolling
- Active navigation link highlighting

---

## Responsive Design

The layout changes depending on screen size:

- On small screens, navigation links stack vertically.
- On larger screens, projects are displayed in two columns.
- Flexbox and CSS Grid were used to control layout.

---

## JavaScript Feature

The JavaScript code listens to scroll events.  
It detects which section is visible and adds an "active" class to the matching navigation link.