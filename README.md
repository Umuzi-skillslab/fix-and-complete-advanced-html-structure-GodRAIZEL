# Media Production Website

## Overview
This project is a responsive multi-page website for a Media Production Company. The purpose of the site is to showcase services such as video production, audio recording, and multimedia solutions, while also providing a portfolio, media samples, and a contact form for potential clients. The website was built using HTML5 and CSS3, with a strong focus on semantic structure, responsiveness, and modern UI design.

---

## Issues Found
The starter code contained several structural and design issues:
- Incorrect use of non-semantic `<div>` elements instead of `<section>`, `<header>`, `<footer>`, and `<nav>`
- Missing viewport meta tag, causing poor responsiveness
- Navigation bar lacked responsiveness and proper structure
- No Flexbox or Grid layouts implemented
- Poor text alignment and inconsistent styling
- Low color contrast affecting readability
- Missing media elements (video, audio, iframe)
- Incomplete form with incorrect input types and no validation
- No hover effects, animations, or transitions
- Lack of accessibility features such as labels and alt attributes

---

## Fixes and Implementations
- Replaced generic `<div>` elements with semantic HTML5 tags
- Added viewport meta tag for responsive design
- Rebuilt navigation using Flexbox and implemented a CSS-only hamburger menu
- Centered and structured content using Flexbox layouts
- Implemented CSS Grid for the portfolio gallery
- Added missing media elements: videos, audio player, and Google Maps iframe
- Improved typography, spacing, and color contrast
- Built a fully functional and validated contact form using proper input types and fieldsets
- Added hover effects and transitions for interactivity

---

## Flexbox Layouts
Flexbox was used extensively for:
- Navigation bar (horizontal layout with responsive wrapping)
- Hero and section alignment (centering content vertically and horizontally)
- Services section (card layout with flexible wrapping)
- Testimonials section (responsive card layout)

Flexbox allowed consistent alignment, spacing, and responsiveness across different screen sizes.

---

## CSS Grid Layout
CSS Grid was implemented in the Portfolio section:
- Used `grid-template-columns` to create a responsive image gallery
- Adjusted layout using media queries (3 columns → 2 → 1)
- Ensured consistent spacing using `gap`

This provided a clean and scalable gallery layout.

---

## Selectors and Pseudo-Classes
Various selectors were used:
- Element selectors (`section`, `nav`, `form`)
- Class selectors (`.hero`, `.services`, `.portfolio`)
- Descendant and child selectors
- Attribute selectors (e.g., `input[type="text"]`)

Pseudo-classes implemented:
- `:hover` (buttons, cards, images)
- `:focus` (form inputs)
- `:checked` (hamburger menu toggle)
- `:first-child` / `:last-child` (where applicable)

---

## Animations, Effects, and Transitions
- Hover animations on service cards and images using `transform: scale()` and `translateY()`
- Smooth transitions using `transition` for hover effects
- Button hover color transitions
- Subtle box-shadow effects for depth

---

## Accessibility Improvements
- Added `<label>` elements for all form inputs
- Included `alt` attributes for all images
- Used semantic HTML for better screen reader support
- Improved color contrast for readability
- Added fallback text for video and audio elements

---

## Cross-Browser Compatibility
- Used standard HTML5 and CSS3 features supported by modern browsers
- Avoided unsupported or experimental CSS
- Tested responsiveness using Chrome DevTools
- Ensured media elements (video/audio) use widely supported formats (MP4, MP3)

---

## How to View Locally
1. Download or clone the project folder
2. Open the folder in a code editor (e.g., VS Code)
3. Open `index.html` in your browser  
   OR  
   Use a Live Server extension for better development experience

---

## Known Issues / Limitations
- No JavaScript functionality (as per project constraints)
- Media files may increase load time if not optimized
- Form does not submit data (no backend integration)
- Limited animations due to CSS-only implementation