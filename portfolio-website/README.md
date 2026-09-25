# Developer Portfolio Website

## Overview

This project is a multi-page portfolio website built using HTML5 and CSS3. The purpose of the website is to showcase my front-end development skills, featured projects, technical experience, and provide visitors with a way to contact me.

The website consists of four pages:

- Home
- About
- Projects
- Contact

The site was created as part of a capstone assessment focused on semantic HTML, accessibility, responsive design, debugging, and CSS styling.

---
## Issues Found

The starter code contained numerous HTML and CSS issues that required correction. Some of the main problems identified included:

1. Missing navigation menu on the homepage.
2. Excessive use of non-semantic div elements.
3. Missing viewport meta tags.
4. Missing image alt text.
5. Missing data table on the About page.
6. Missing project section on the Projects page.
7. Missing form labels.
8. Insufficient form input variety.
9. Missing HTML validation attributes.
10. Poor colour contrast.
11. Missing navigation styling.
12. Missing hover and focus states.
13. Missing table styling.
14. Inconsistent page structure.
15. Footer alignment issues.
16. Missing responsive design considerations.
17. Limited CSS selector variety.
18. Invalid HTML structure in contact.html.
19. Incorrect CSS submit button selector.
20. Missing accessibility enhancements.

---

## Fixes Implemented
The following improvements were made:

- Replaced generic div elements with semantic HTML5 landmarks.
- Added consistent navigation across all pages.
- Added descriptive alt text to all images.
- Created a fully structured skills table.
- Added a third project section.
- Improved colour contrast using an accessible colour palette.
- Added responsive image styling.
- Added form labels and validation attributes.
- Implemented focus states and hover effects.
- Styled navigation, tables, forms, and content sections.
- Fixed all HTML structure issues identified by the validator.
- Corrected CSS selector errors.
- Added a responsive media query for smaller screens.
- Improved overall layout and spacing using the CSS box model.

---
## HTML Structure and Semantic Elements

The website uses semantic HTML5 elements throughout:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<footer>`

These elements improve accessibility, maintainability, and document structure.
Navigation is present on all four pages and allows users to move throughout the site consistently.

The About page contains a properly structured table using:

- `<table>`
- `<caption>`
- `<thead>`
- `<tbody>`
- `<th>`
- `<td>`

The Contact page contains an accessible form using labels, validation attributes, fieldsets, and legends.

---

## CSS Styling Approach

The stylesheet was organised into logical sections:

- CSS variables and global styles
- Header and navigation
- Layout and containers
- Images
- Tables
- Forms
- Footer
- Responsive layouts

The project demonstrates multiple selector types:
- Element selectors
- Class selectors
- ID selectors
- Descendant selectors
- Pseudo-class selectors

Pseudo-classes used include:

- `:hover`
- `:focus`
- `:nth-child()`

The box model is demonstrated through extensive use of:

- Margin
- Padding
- Border

Flexbox was used for navigation and form layouts.

---

## Accessibility Improvements

Several accessibility improvements were implemented:

- Semantic HTML landmarks.
- Descriptive alt text for images.
- Proper heading hierarchy.
- Form labels linked to inputs.
- Fieldset and legend elements for grouped controls.
- Visible keyboard focus indicators.
- Accessible colour contrast ratios.
- HTML5 validation attributes.
- Active page indicators using `aria-current="page"`.

These changes improve usability for keyboard users and assistive technologies.

---

## Screenshots
 
The following screenshots are included in the screenshots folder:
 
- Home Page Screenshot (`After-Homepage.png`)
- About Page Screenshot (`After-About.png`)
- Projects Page Screenshot (`After-Project1.png/After-Project2.png`)
- Contact Page Screenshot (`After-ContactMe.png`)
- Contact Form Screenshot (`ContactForm.png`)
- Skills Table Screenshot (`Table.png`)
- Navigation Hover Effect Screenshot (`NavbarHover.png`)
 
These screenshots demonstrate the completed website, navigation functionality, responsive layout, styled form, and accessible table implementation.

---

## How to View the Website

1. Clone the repository:

git clone https://github.com/ZubaidaKhan69/Capstone-2.git

2. Open the project folder.
3. Locate the file named `index.html`.
4. Open `index.html` in a web browser.
5. Use the navigation menu to browse between all four pages.

---
## Reflection

One of the biggest challenges during this project was identifying and correcting the large number of HTML and CSS issues present in the starter code. Debugging validation errors required careful testing using the W3C validators and reviewing document structure across all pages.

I improved my understanding of semantic HTML, accessibility requirements, form validation, CSS selectors, responsive layouts, and code organisation. Through the debugging process, I learned how small structural errors can impact validation, accessibility, and user experience. The project also reinforced the importance of planning, testing, and maintaining consistent design patterns throughout a website.

---

## Author

Zubaida Khan

Front-End Developer Portfolio Project

