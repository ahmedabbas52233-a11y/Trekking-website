# 🏔️ Uncharted Travels — Pakistan's Premier Trekking Website

[![pages-build-deployment](https://github.com/ahmedabbas52233-a11y/Trekking-website/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/ahmedabbas52233-a11y/Trekking-website/actions/workflows/pages/pages-build-deployment)
[![Live Site](https://img.shields.io/badge/Live%20Site-Vercel-black?logo=vercel)](https://trekking-website-tawny.vercel.app)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A responsive, multi-page travel agency website showcasing adventure treks and family tours across Pakistan. Built with pure **HTML5, CSS3, and Vanilla JavaScript** — no frameworks, no shortcuts.

> 🌐 **Live Demo:** [trekking-website-tawny.vercel.app](https://trekking-website-tawny.vercel.app)

---

## 📸 Preview

![Trekking Website Preview](preview.gif)

---

## ✨ Features

| Feature | Details |
|---|---|
| 📱 Responsive Design | Adapts seamlessly to desktop, tablet & mobile |
| 🧭 5-Page Layout | Home · Destinations · Family Treks · Wild Treks · Contact |
| 🖼️ Image Galleries | Showcasing Hunza, Skardu, Deosai & Fairy Meadows |
| 🎬 Scroll Animations | Reveal effects using Intersection Observer API |
| 🔍 Search Bar | Live destination search on the Destinations page |
| 📬 Contact Form | Floating-label inputs with live validation |
| 🌐 Sticky Nav | Frosted-glass blur effect on scroll |
| 🚀 CI/CD | Auto-deployed via GitHub Actions to Vercel |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure, ARIA accessibility attributes
- **CSS3** — Flexbox, Grid, custom properties (design tokens), `clamp()` for fluid typography, transitions & transforms
- **Vanilla JavaScript** — Intersection Observer API, scroll event handling, DOM manipulation
- **Font Awesome 6** — Icon library
- **Google Fonts** — Cormorant Garamond (display) + Jost (body)
- **Vercel** — Deployment & hosting
- **GitHub Actions** — CI/CD pipeline

---

## 📂 Project Structure

```
Trekking-website/
├── index.html            # Landing page — hero, destinations preview, CTA
├── destination.html      # Full destinations gallery with search
├── family.html           # Family trek packages & gallery
├── wildtrek.html         # Wild trek adventures & gallery
├── contact.html          # Contact form with floating labels
├── StyleSheet/
│   ├── index style.css
│   ├── destination style2.css
│   ├── contact style3.css
│   ├── wild style4.css
│   └── familystyle.css
├── htmlpictures/         # Site images & logo assets
├── Csspictures/          # Background & hero images
├── preview.gif           # Animated site preview
└── README.md
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/ahmedabbas52233-a11y/Trekking-website.git

# Navigate into the project
cd Trekking-website

# Open in browser (no build step needed)
open index.html
```

> No dependencies. No package manager. Just open `index.html` and go.

---

## 🧠 What I Learned

Building this project taught me things no tutorial could — real decisions, real tradeoffs:

- **CSS Design Tokens** — Using `:root` custom properties (`--forest`, `--gold`, `--ink`) to manage a consistent color system across 5 pages without repeating values. Changing a brand color meant editing one line.

- **Intersection Observer API** — Replaced scroll event listeners with `IntersectionObserver` for reveal animations. This is significantly better for performance since it doesn't fire on every scroll pixel — it only triggers when an element enters the viewport.

- **`clamp()` for Fluid Typography** — Used `font-size: clamp(3rem, 7vw, 6rem)` so headings scale naturally with the viewport instead of relying on multiple breakpoints. Fewer media queries, cleaner code.

- **Flexbox + CSS Grid Together** — Learned when to use each: Grid for 2D page layouts (galleries, card grids), Flexbox for 1D alignment (nav bar, form rows). Using both together rather than picking one made layouts much more intuitive.

- **CI/CD with GitHub Actions** — Set up automatic deployment so every `git push` to main triggers a fresh build and deploy to Vercel. This mirrors a real production workflow.

- **Accessibility Basics** — Added `aria-label` attributes to interactive elements, `alt` text to all images, and semantic HTML tags (`<nav>`, `<section>`, `<main>`) throughout.

---

## 🗺️ Pages Overview

### 🏠 Home (`index.html`)
Full-screen hero with a parallax background image, animated headline, and scroll indicator. Destination preview cards with hover zoom effects and a bold call-to-action banner.

### 🗺️ Destinations (`destination.html`)
Live search bar filtering Pakistan's top trekking destinations. Masonry-style gallery with scroll-triggered reveal animations for Hunza, Skardu, Deosai, and more.

### 🏕️ Family Treks (`family.html`)
Family-friendly tour packages with photo galleries and descriptive layout cards. Designed for a warmer, approachable visual tone.

### 🏔️ Wild Treks (`wildtrek.html`)
Adventure-focused page with dramatic full-width imagery, package highlights, and a CTA band with an italic gold accent.

### 📬 Contact (`contact.html`)
A polished contact form with floating labels (labels animate up on focus), a custom-styled select dropdown, and direct contact info cards with hover effects.

---

## 📈 Future Improvements

- [ ] Add JavaScript form validation with error messages
- [ ] Integrate a map (Leaflet.js or Google Maps) on the Destinations page
- [ ] Add a dark mode toggle
- [ ] Implement a booking/enquiry system
- [ ] Optimize images with WebP format for faster load times
- [ ] Add a mobile hamburger menu

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🤝 Connect

Made with ❤️ by **Ahmad Abbas**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?logo=github)](https://github.com/ahmedabbas52233-a11y)
