# Developer Portfolio Website

A clean, responsive, and WCAG-accessible multi-page portfolio website showcasing my front-end web development projects, skills matrix, and contact form.

## Overview
This repository contains a refactored and complete implementation built with semantic HTML5 and CSS3. The platform highlights my core projects—such as the **Little Lemon React Capstone Web App**—while demonstrating mastery of accessible design, responsive grid layouts, and zero-error W3C standard code.

---

## Major Issues Identified & Fixes Implemented

* **Landmark Refactoring:** Eliminated non-semantic `<div>` clutter by implementing `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` elements across all 4 pages.
* **Unified Navigation:** Implemented a robust 16-link navigation architecture (4 links per page) featuring interactive hover and focus visual feedback.
* **Accessible Contact Form:** Constructed a contact form using 5 distinct input controls (`text`, `email`, `select`, `radio`, `textarea`) bound to explicit `<label>` tags with client-side HTML5 validation.
* **Data Presentation:** Designed a skill matrix table on `about.html` featuring custom zebra-striping via CSS pseudo-class selectors.
* **Color Contrast:** Selected WCAG AAA compliant text and surface colors, ensuring contrast ratios exceed 4.5:1.

---

## Technical Features & CSS Approach

* **Selector Variety:** Utilizes Element, Class, ID (`#main-content`), Descendant (`nav ul li`), and Pseudo-class (`:hover`, `:focus`, `:nth-child`) selectors.
* **Box Model Discipline:** Strict box-model management using `margin`, `padding`, `border`, and `box-sizing: border-box`.
* **Zero W3C Validation Errors:** Fully verified against the W3C HTML5 and W3C CSS Validation Services.

---

## Local Viewing Instructions

1. Clone this repository locally:
   ```bash
   git clone [https://github.com/ZubaidaKhan69/Capstone-2.git](https://github.com/ZubaidaKhan69/Capstone-2.git)