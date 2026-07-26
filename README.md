# LBRP Ritual Guide

An illuminated, animated guide for learning and practicing the **Lesser Banishing Ritual of the Pentagram (LBRP)** — one of the foundational rituals of the Western esoteric tradition (Hermetic Qabalah / the Golden Dawn).

Live site → **[marcusg999.github.io/LBRPGuide.github.io](https://marcusg999.github.io/LBRPGuide.github.io/)**

---

## About the App

The LBRP Ritual Guide is a single-page web app that teaches the complete ritual through a lifelike 2D canvas animation. A robed practitioner moves through every phase — the opening Qabalistic Cross, the tracing of the four banishing pentagrams, and the calling of the Archangels — while synced captions name each gesture and vibrated Name. Beneath the animation, an ordered reference walks through the rite step by step.

The visual identity is a **"candlelit initiate's grimoire"**: an obsidian night-temple ground, antique-gold accents, elemental colours reserved for the four quarters, and a classical serif type system.

---

## The Animation

The centrepiece is a hand-built canvas engine designed to move like a real person rather than snap between static poses:

- **Two-bone inverse kinematics** for the arms — the elbow bends naturally as the hand reaches each target (forehead, shoulders, heart, or out to a quarter).
- **Eased pose tweening** — every gesture is smoothed toward its target with frame-rate-independent damping, giving deliberate, ritual-paced motion.
- **Secondary motion** — continuous breathing, idle weight-shift sway, and robe/hem follow-through keep the figure alive between gestures.
- **Light-projection tracing** — the practitioner projects a beam of light that traces each **banishing earth pentagram** in the correct stroke order (lower-left → crown → lower-right → upper-left → upper-right), building the star as it draws.
- **A faithful timeline** — the Qabalistic Cross, the four quarters with their divine Names, the carried circle of light, the Archangel invocation, and the closing six-rayed star, each with a caption naming the gesture and word.

The ritual movements were researched against traditional Golden Dawn sources to keep the sequence, stroke order, directions, divine Names, and Archangel placements accurate.

---

## The Rite (as taught in the app)

### I. The Qabalistic Cross
| Gesture | Word | Meaning |
|---------|------|---------|
| Touch the forehead | *Atah* | Thou art |
| Draw down to the breast | *Malkuth* | the Kingdom |
| Touch the right shoulder | *Ve-Geburah* | and the Power |
| Touch the left shoulder | *Ve-Gedulah* | and the Glory |
| Clasp the hands at the heart | *Le-Olam, Amen* | to the ages, Amen |

### II. The Four Pentagrams (turning clockwise)
| Quarter | Element | Divine Name | Vibration |
|---------|---------|-------------|-----------|
| East | Air | YHVH | Yod-Heh-Vav-Heh |
| South | Fire | ADNI | Adonai |
| West | Water | AHIH | Eheieh |
| North | Earth | AGLA | Agla |

### III. The Archangels
| Direction | Archangel | Element |
|-----------|-----------|---------|
| Before me · East | Raphael | Air |
| Behind me · West | Gabriel | Water |
| On my right hand · South | Michael | Fire |
| On my left hand · North | Uriel | Earth |

### IV. The Six-Rayed Star
*"For about me flames the Pentagram, and within me shines the Six-rayed Star."* The Qabalistic Cross is repeated to close, and the circle stands complete.

---

## Features

- **Lifelike ritual animation** with Begin / Pause / Replay and Reset controls, a progress bar, and live captions.
- **Ordered reference** — the full rite laid out as a numbered sequence, with the Qabalistic Cross gestures, the four quarter cards (colour-coded by element), the Archangels, and the closing.
- **"Why practice" essay** — a rewritten, plain-language account of what the daily rite offers students of magick and meditation.
- **Light & dark themes** — an obsidian night temple by default, or an illuminated-parchment manuscript in light mode. The choice is saved to `localStorage` and respects the OS `prefers-color-scheme` on first load. The animation stage stays a dark "window into the temple" in both themes so the figure always reads clearly.
- **Accessibility** — semantic HTML5, `aria-live` captions, keyboard-visible focus rings, and a full static tableau of the completed circle for visitors with `prefers-reduced-motion`.

---

## Running Locally

No build step required — a single self-contained HTML file (typefaces load from Google Fonts).

```bash
git clone https://github.com/marcusg999/LBRPGuide.github.io.git
cd LBRPGuide.github.io
python3 -m http.server 8080
# open http://localhost:8080
```

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | Semantic HTML5 |
| Styling | Custom CSS with design tokens; dual light/dark themes |
| Type | Cinzel, Cormorant Garamond & EB Garamond (Google Fonts) |
| Animation | Hand-written HTML Canvas 2D engine — two-bone IK, eased tweening, procedural secondary motion |
| Reveal / theming | `IntersectionObserver` + CSS custom properties + `localStorage` |
| Hosting | GitHub Pages |

---

## Deployment

Deployed automatically via **GitHub Pages** from the `main` branch — push to `main` and the live site updates within minutes.

---

## Disclaimer

This animation is a learning aid and visualisation tool. Real practice asks for your own focus, intent, breath, and energy — more than any figure on a screen can show.
