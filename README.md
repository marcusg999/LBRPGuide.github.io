# LBRP Ritual Guide

An interactive, animated guide for learning and practicing the **Lesser Banishing Ritual of the Pentagram (LBRP)** — one of the foundational rituals of Western esoteric tradition.

Live site → **[marcusg999.github.io/LBRPGuide.github.io](https://marcusg999.github.io/LBRPGuide.github.io/)**

---

## About the App

The LBRP Ritual Guide is a single-page web app that teaches the complete Lesser Banishing Ritual of the Pentagram through a step-by-step 2D canvas animation. It walks practitioners through each phase of the ritual — from the opening Qabalistic Cross through the four directional pentagrams and the invocation of the Archangels — providing a visual reference that complements real practice.

The app is designed with a modern **iPhone-first layout** that feels at home on any device, from a phone screen to a desktop browser.

---

## Features

### Interactive Canvas Animation
- A 2D animated canvas visualizes each stage of the ritual in sequence.
- **Start** button runs the full animation from the Qabalistic Cross through to the final protective circle.
- **Reset** button clears the canvas so you can restart at any time.
- The canvas resizes responsively to fit any screen width.

### Ritual Steps Reference
Four clearly labelled sections cover every part of the ritual:

| Step | Content |
|------|---------|
| **1. The Qabalistic Cross** | Five movements with their Hebrew phrases and translations |
| **2. The Pentagrams** | The four cardinal pentagrams and their associated colours |
| **3. Calling the Archangels** | Raphael, Michael, Gabriel, and Uriel and their directions |
| **4. Completion** | The closing circle of all four glowing pentagrams |

### The Value of LBRP
A dedicated section explains why the LBRP matters, covering eight key benefits for students of magick and meditation:

- Energy Cleansing
- Psychic Protection
- Concentration Enhancement
- Elemental Balancing
- Meditative Framework
- Energetic Attunement
- Psychological Integration
- Preparation for Advanced Work

### Light & Dark Mode
- Toggle between light and dark themes with a single tap.
- Your preference is saved to `localStorage` and restored on every visit.
- The app also respects your operating system's `prefers-color-scheme` setting on first load.

### iPhone-First Design
- Narrow, app-like column layout (max 430 px) optimised for one-handed mobile use.
- Sticky frosted-glass header with `backdrop-filter` blur.
- iOS safe-area insets (`env(safe-area-inset-*)`) for full support of notched and home-bar devices.
- Apple system font stack (`-apple-system`, `SF Pro Display/Text`).
- Rounded cards, subtle shadows, and iOS-inspired colour tokens.

### Smooth Animations
- **Page load:** the hero section fades and slides in on arrival.
- **Scroll reveal:** each section card animates into view as you scroll, with a gentle stagger between siblings.
- **Micro-interactions:** buttons scale slightly on press for tactile feedback.
- All motion is automatically disabled when the user has `prefers-reduced-motion` enabled, ensuring full accessibility.

### Accessibility
- Semantic HTML5 structure (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Sections labelled with `aria-labelledby`; icon buttons labelled with `aria-label`.
- Keyboard-navigable with a clear `:focus-visible` ring.
- Sufficient colour contrast in both light and dark themes.

---

## Running Locally

No build step required. The app is a single self-contained HTML file with no external dependencies.

```bash
# Clone the repo
git clone https://github.com/marcusg999/LBRPGuide.github.io.git
cd LBRPGuide.github.io

# Serve with any static file server, e.g.:
python3 -m http.server 8080
# Then open http://localhost:8080 in your browser
```

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | Semantic HTML5 |
| Styling | Custom CSS with CSS custom properties (design tokens) |
| Animation | CSS `@keyframes` + `IntersectionObserver` scroll reveal |
| Canvas | Native HTML Canvas 2D API |
| Theming | CSS custom properties + `localStorage` |
| Hosting | GitHub Pages |

---

## Deployment

The site is deployed automatically via **GitHub Pages** from the `main` branch. No CI/CD configuration is required — push to `main` and the live site updates within minutes.
