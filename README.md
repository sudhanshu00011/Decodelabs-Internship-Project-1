# 🌐 DecodeLabs — Project 1: Responsive Frontend Interface

> **Industrial Training Kit · Batch 2026 · Powered by DecodeLabs**

A fully responsive, accessible, and production-grade frontend web application built using **pure HTML5, CSS3, and Vanilla JavaScript** — no frameworks, no libraries..

## 🎯 Project Overview

This is **Project 1** of the DecodeLabs Full Stack Development internship program. The goal was to build a complete responsive frontend interface — the "interface phase" — before connecting any backend databases.

The focus: **Adaptability over fixed dimensions.** Every layout decision was made mobile-first, and expanded outward.

---

## ✨ Features

- ✅ **Fully Responsive** — works seamlessly on mobile, tablet, and desktop
- ✅ **Mobile-First Architecture** — built from smallest screen up
- ✅ **Semantic HTML5** — proper use of `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`
- ✅ **CSS Grid + Flexbox** — Grid for macro layout, Flexbox for components
- ✅ **Fluid Typography** — using `clamp()` for smooth font scaling
- ✅ **Accessible (WCAG)** — ARIA labels, keyboard navigation, screen reader support
- ✅ **Scroll Reveal Animations** — staggered entrance animations via IntersectionObserver
- ✅ **Hamburger Menu** — animated mobile navigation with toggle state
- ✅ **Active Nav Highlighting** — tracks current section on scroll
- ✅ **Back-to-Top Button** — appears on scroll, smooth scroll to top
- ✅ **Zero Dependencies** — no Bootstrap, no jQuery, no frameworks

---

## 🛠️ Tech Stack

| Technology | Role |
|------------|------|
| **HTML5** | Structure & Semantic Landmarks |
| **CSS3** | Styling, Grid, Flexbox, Animations |
| **Vanilla JavaScript** | Interactivity & State Management |

---

## 🎨 Design System

### Color Palette (DecodeLabs 2025)

| Name | Hex | Usage |
|------|-----|-------|
| 🟫 Mocha Mousse | `#A5856E` | Primary brand, CTAs, accents |
| 🔵 Ethereal Blue | `#A0D4E0` | Trust, tags, highlights |
| ⬜ Moonlit Grey | `#F2F0EA` | Backgrounds, surfaces |
| 🖤 Ink | `#2B2118` | Body text, headings |

### Typography

| Role | Font | Weights |
|------|------|---------|
| **Headlines** | Montserrat | 400, 600, 800 |
| **Body** | Lora | 400, 600 |

> Max 2 font families · Max 3 font weights (as per DecodeLabs spec)

---

## 📐 Layout Architecture

```
┌─────────────────────────────────────┐
│           HEADER / NAV (60px)       │  ← Sticky, Flexbox
├─────────────────────────────────────┤
│           HERO SECTION (360px)      │  ← CSS Grid, radial gradients
├─────────────────────────────────────┤
│     FEATURES GRID (3-col desktop)   │  ← CSS Grid, responsive
├────────────────────────┬────────────┤
│   CONTENT GRID         │  SIDEBAR   │  ← Grid + Flexbox
│   (articles/cards)     │  (widgets) │
├────────────────────────┴────────────┤
│        ROADMAP (6 steps)            │  ← Timeline layout
├─────────────────────────────────────┤
│           CTA BANNER                │
├─────────────────────────────────────┤
│       FOOTER (4-col desktop)        │  ← Grid, 20px margin
└─────────────────────────────────────┘
```

---

## 📱 Responsive Breakpoints

```css
/* Mobile First — default styles */
/* Single column layout */

/* Tablet — 768px and above */
@media (min-width: 768px) { ... }   /* 2-col grid, sidebar appears */

/* Desktop — 1024px and above */
@media (min-width: 1024px) { ... }  /* 3-col grid, full layout */
```

---

## 🗺️ Execution Roadmap (How I Built It)

Following the DecodeLabs 6-step framework:

| Step | Phase | What I Did |
|------|-------|------------|
| 1️⃣ | **Discovery** | Defined the "How Might We" problem statement |
| 2️⃣ | **Wireframe** | Sketched grayscale, mobile-first layouts |
| 3️⃣ | **Semantics** | Wrote HTML structure with proper landmark elements |
| 4️⃣ | **Style** | Applied CSS Grid, Flexbox, and the 2025 color palette |
| 5️⃣ | **Logic** | Added JavaScript interactivity (menu, scroll effects) |
| 6️⃣ | **Audit** | Checked Lighthouse scores, WCAG compliance |

---

## 🚀 Getting Started

### View Locally

No build tools or server required. Just open the file:

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/decodelabs-project1.git

# Navigate into the folder
cd decodelabs-project1

# Open in browser (double-click or use terminal)
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

### Deploy to GitHub Pages

```bash
# 1. Push your code to GitHub
git add .
git commit -m "feat: initial project 1 submission"
git push origin main

# 2. Go to your repo on GitHub
# Settings → Pages → Source: Deploy from branch → main → / (root) → Save

# 3. Your site will be live at:
# https://YOUR-USERNAME.github.io/decodelabs-project1
```

---

## ♿ Accessibility

This project follows **WCAG 2.1** guidelines:

- All images have descriptive `alt` attributes
- Interactive elements have `aria-label` attributes
- Keyboard navigation is fully supported (Tab, Enter, Escape)
- Color contrast ratios meet AA standards
- Hamburger menu uses `aria-expanded` state
- Landmark roles are properly defined for screen readers

---

## 📊 Performance Targets

| Metric | Target |
|--------|--------|
| Lighthouse Performance | 90+ |
| Largest Contentful Paint (LCP) | < 2.5s |
| Cumulative Layout Shift (CLS) | < 0.1 |
| Accessibility Score | 95+ |

> Run `Lighthouse` in Chrome DevTools → right-click → Inspect → Lighthouse tab to audit.

---

## 🧠 Key Learnings

- Why **semantic HTML** matters beyond just structure (SEO, accessibility, AI parsing)
- The difference between **CSS Grid** (2D layouts) and **Flexbox** (1D components)
- **Mobile-first** is a mindset, not just a media query order
- `clamp()` for typography eliminates the need for multiple font-size breakpoints
- `IntersectionObserver` is far more performant than scroll event listeners
- Good UX is invisible — the best design is the one users don't notice

---

## 👤 Author

**Your Name**
- GitHub: [@sudhanshu00011](https://github.com/sudhanshu00011)
- LinkedIn: [linkedin.com/in/sudhanshu-prasad-023957289](https://linkedin.com/in/sudhanshu-prasad-023957289)
- Email: sudhanshuprasad148@gmail.com

---
