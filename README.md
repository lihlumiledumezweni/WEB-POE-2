# HLUMIE'S NGO - Web Development POE (WEDE5020)

**Student Name:** Lihlumile Dumezweni  
**Student Number:** ST10507456  
**Module:** Web Development (WEDE5020)  
**Project:** HLUMIE'S NON-PROFIT ORGANIZATION FOR WOMEN  

---

## Project Overview
HLUMIE'S NGO is a multi-page web platform designed to empower women by providing access to emergency shelter, psychosocial support, legal advocacy, and educational resources. This repository tracks the full development lifecycle from Part 1 structure to Part 2 styling and responsive design.

---

## Part 2 Implementation Summary

### Design System & CSS Architecture
* **External Stylesheet:** All layout rules, resets, and typography styles are centralized in `css/style.css`.
* **CSS Variables (`:root`):** A custom color palette was defined to ensure brand consistency:
  * Eerie Black: `#1B1B1B`
  * Amaranth Purple: `#AB274F`
  * Rose Pompadour: `#ED7A9E`
  * Light Background: `#FFF8F9`
* **Interactive Pseudo-Classes:** Enhanced navigation and interactive elements using `:hover`, `:focus`, and `:active` states.
* **Semantic Layout:** Styled semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) with Flexbox for dynamic desktop alignment.

### Responsive Design
* **Tablet Breakpoint (`768px`):** Stacked header elements and adjusted container margins for tablet readability.
* **Mobile Breakpoint (`480px`):** Converted horizontal navigation menus into full-width vertical tap targets and configured flexible images (`max-width: 100%`).

---

## Part 1 Feedback & Changelog

### Lecturer Feedback Status
* **Status:** Pending formal lecturer grading.

### Self-Review & Refinement Updates (Pre-Grading)
* **CSS Linking:** Ensured all 5 HTML pages (`index.html`, `about.html`, `services.html`, `resources.html`, `contact.html`) link cleanly to `css/style.css`.
* **Contact Form Implementation:** Replaced duplicated template content on `contact.html` with a complete functional contact form.
* **Semantic Navigation:** Structured navigation links inside semantic `<ul>` lists across all pages.

---

## References

* FontAwesome. 2026. *Font Awesome Icons & Toolkit*. Available at: https://fontawesome.com [Accessed 12 August 2026].
* Google Fonts. 2026. *Playfair Display & Inter Font Families*. Available at: https://fonts.google.com [Accessed 12 August 2026].
* Mozilla Developer Network. 2026. *HTML5 & CSS3 Web Development Standards and Layouts*. Available at: https://developer.mozilla.org [Accessed 12 August 2026].
* People Opposing Women Abuse. 2026. *Services and Support for Women Surviving Abuse*. Available at: https://www.powa.co.za [Accessed 12 August 2026].
