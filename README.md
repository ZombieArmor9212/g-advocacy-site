Owned by: ZombieArmor9212

This is a high-performance, responsive web platform built to advocate for environmental sustainability in the Philippines. The project features a premium "Glassmorphism" UI, custom parallax scrolling logic, and a dynamic interactive member system.

---

CORE FEATURES

* Custom Parallax Engine: A hand-coded JavaScript scroll system that calculates viewport progress to move backgrounds within a "Safe Zone," preventing the "black edge" glitch.
* Smart-Reset UI: An interactive card system for team members that allows for instant switching between states without animation clipping.
* Filipino-Premium Aesthetic: A design language combining modern translucent glass elements with traditional Filipino themes (Gold, Obsidian, and Nature).
* Responsive Architecture: Fully fluid layouts using clamp() and vw units for seamless viewing on mobile and desktop.

---

TECH STACK

* Frontend: HTML5, CSS3 (Custom Properties & Flexbox)
* Logic: Vanilla JavaScript (ES6+)
* Typography: Google Fonts (Playfair Display & Montserrat)
* Hosting: GitHub Pages

---

TECHNICAL DEEP DIVE

1. The "Smart-Reset" Logic
To ensure a fluid user experience on the grupo.html page, I implemented a decoupled state-management function. This allows the UI to instantly close any active card and reset the overlay before initializing a new animation.

2. Safe Parallax Calculation
The background movement is calculated based on scroll percentage multiplied by a defined safety buffer (e.g., 0.25). This ensures the image never moves beyond its zoom boundaries, maintaining a seamless visual experience.

---

CONTRIBUTION & OWNERSHIP

ZombieArmor9212
* Full-Stack Development (Code & Logic)
* UI/UX Design & Architecture
* Repository Management & Hosting

---

LICENSE
This project was developed for educational and advocacy purposes.
