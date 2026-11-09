# 🎨 CSS Animation, Transition, and Transform Showcase

An interactive web application demonstrating modern CSS animation techniques, including keyframes, transitions, and transforms to create dynamic UI elements.

---

## 🚀 Features & Project Structure

The layout is split into three main semantic sections (`<header>`, `<main>`, and `<footer>`) and features:

- **Keyframe Animations (`@keyframes`):** 
  - `@keyframes bounce` animates a bouncing ball element across multiple percentage keyframes (`0%`, `50%`, `100%`), altering position, scale, and background color.
  - `@keyframes fadeInSlide` creates a smooth fade-in and slide-down effect for the header subtitle upon page load.

- **Transitions (`transition`):**
  - Smooth hover transitions applied to buttons, image containers, and text links for background color shifts, box shadows, and opacity changes.
  - Animated underline pseudo-element on links (`.styled-link`).

- **Transforms (`transform`):**
  - **Skew:** Applied to the main header title (`transform: skewX(-10deg)`) for a stylized 3D tilt.
  - **Scale & Rotate:** Used on image hover (`transform: scale(1.08) rotate(1deg)`).
  - **Translate:** Used on button hover state (`transform: translateY(-4px) scale(1.05)`) to create a smooth lifting effect.

- **Combined Effects:** 
  - The main action button combines state transition timings with dynamic `translateY` scaling and focus states.

---

## 📁 File Overview

```text
├── index.html     # Semantic HTML5 layout with header, main content, and footer
├── styles.css     # CSS file containing keyframes, transforms, and transitions
└── README.md      # Project documentation and submission notes