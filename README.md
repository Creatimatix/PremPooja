# Prem Pooja Textile Processors Pvt. Ltd. — Website

A complete, production-ready single-page website for **Prem Pooja Textile Processors Pvt. Ltd.**, built as a single `index.html` file with all CSS and JavaScript embedded inline. No build tools, no npm, no external dependencies beyond Google Fonts and Unsplash images.

---

## 🏢 Company Info

| Field       | Details                              |
|-------------|--------------------------------------|
| Company     | Prem Pooja Textile Processors Pvt. Ltd. |
| Tagline     | Specialist in Bleaching, Dyeing & Printing |
| Founded     | 1998                                  |
| Phone       | +91 98195 70709 / +91 98202 80057    |
| Email       | prempoojatex@hotmail.com             |
| Branch 1    | Plot No. 45, MIDC Industrial Area, Andheri East, Mumbai – 400093 |
| Branch 2    | Gala No. 12, Badlapur Industrial Estate, Badlapur (W), Thane – 421503 |

---

## 📁 File Structure

```
Prem Pooja Textiles/
├── index.html      ← Complete website (HTML + CSS + JS, single file)
└── README.md       ← This documentation
```

---

## 🌐 Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Navbar** | Sticky header with logo (🏇 unicode horse-rider), company name, nav links, hamburger menu |
| 2 | **Hero** | Full-viewport banner with textile background image, tagline, CTA buttons, stats bar |
| 3 | **About** | Company story, mission/vision, founded values with image and badge |
| 4 | **Services** | 6 service cards: Bleaching, Dyeing, Printing, Finishing, Fabric Processing, Quality Testing |
| 5 | **Why Choose Us** | Animated stats counters (25+ yrs, 500+ clients, 1000+ fabrics, 2 branches) + 6 differentiator cards |
| 6 | **Process** | 5-step workflow: Fabric Intake → Pre-treatment → Processing → Quality Check → Delivery |
| 7 | **Gallery** | CSS grid of 6 textile/fabric images from Unsplash |
| 8 | **Industries** | 5 industries served: Garments, Home Textiles, Industrial Fabrics, Fashion, Export Houses |
| 9 | **Testimonials** | 3 dummy client testimonials with star ratings and author avatars |
| 10 | **Contact** | 2 branch cards, quick contact links, contact form with validation |
| 11 | **Footer** | Logo, 4-column grid (brand, quick links, services, contact), social icons, copyright |

---

## 🎨 Design System

### Colors
| Variable       | Value       | Usage               |
|----------------|-------------|---------------------|
| `--lime`       | `#B5CC00`   | Primary brand color |
| `--lime-dark`  | `#8fa000`   | Hover states        |
| `--lime-light` | `#d4e84a`   | Accents             |
| `--dark`       | `#1a1a1a`   | Primary dark/text   |
| `--dark2`      | `#2c2c2c`   | Cards/sections      |
| `--black`      | `#111111`   | Footer background   |
| `--white`      | `#ffffff`   | Light backgrounds   |
| `--off-white`  | `#f5f5f5`   | Alternating sections |

### Typography
- **Headings**: Montserrat (Google Fonts) — weights 600, 700, 800, 900
- **Body**: Open Sans (Google Fonts) — weights 400, 500, 600
- Fluid font sizing with `clamp()` for responsive headings

---

## ⚡ Features

### Interactivity
- **Sticky navbar** — transparent over hero, becomes white with shadow on scroll
- **Active nav highlighting** — current section link highlighted as user scrolls
- **Hamburger menu** — animated toggle with accessible ARIA attributes
- **Smooth scrolling** — all anchor links use `scrollTo` with 78px navbar offset
- **Animated counters** — stats count up with eased animation on scroll into view
- **Fade-in on scroll** — `IntersectionObserver` triggers CSS transitions for elements
- **Gallery hover** — scale transform + overlay text reveal on hover
- **Service cards** — lift + bottom-border slide animation on hover
- **Contact form** — client-side validation, loading state, success message
- **Scroll-to-top button** — appears after scrolling 300px, smooth scroll back

### Responsive Design
- **Desktop** (>1100px): Full multi-column layouts
- **Tablet** (768–1100px): 2-column grids, stacked where appropriate
- **Mobile** (<768px): Single-column, hamburger menu, stacked content
- **Small mobile** (<520px): Optimised font sizes, single-column gallery

### Accessibility
- Semantic HTML5 elements (`<nav>`, `<section>`, `<article>`, `<footer>`, etc.)
- ARIA attributes on interactive elements (`aria-label`, `aria-expanded`, `aria-controls`, `aria-hidden`, `aria-live`)
- Skip links via landmark roles
- `alt` text on all images
- Proper heading hierarchy (h1 → h2 → h3 → h4)
- Focus-visible states on form inputs
- Form labels properly associated with inputs

---

## 🖼️ Images Used

All images from [Unsplash](https://unsplash.com) — free to use, no attribution required under Unsplash License.

| Usage | URL |
|-------|-----|
| Hero background | `photo-1558618666-fcd25c85cd64` |
| About / Textile mill | `photo-1586201375761-83865001e31c` |
| Gallery — Colourful fabrics | `photo-1558769132-cb1aea458c5e` |
| Gallery — Cotton fabric | `photo-1620799140408-edc6dcb6d633` |
| Gallery — Printing | `photo-1607082348824-0a96f2a4b9da` |
| Gallery — Quality lab | `photo-1559056199-641a0ac8b55e` |

---

## 🚀 How to Use

1. Open `index.html` in any modern web browser — no server needed.
2. For deployment, upload `index.html` to any static hosting:
   - [GitHub Pages](https://pages.github.com)
   - [Netlify](https://netlify.com) (drag-and-drop deploy)
   - [Vercel](https://vercel.com)
   - Any web hosting via FTP/cPanel

### Local preview
```bash
# Option 1 – Open directly
open index.html

# Option 2 – Python simple server
python3 -m http.server 8080
# Then visit http://localhost:8080

# Option 3 – Node http-server
npx http-server .
```

---

## 🔧 Customisation Guide

### Update contact details
Search for the phone numbers and email in `index.html`:
```
9819570709  →  replace with actual number
9820280057  →  replace with actual number
prempoojatex@hotmail.com  →  replace if needed
```

### Update addresses
Search for `MIDC Industrial Area` and `Badlapur Industrial Estate` blocks and update inline.

### Change primary colour
Update the CSS variable at the top of the `<style>` block:
```css
:root {
  --lime: #B5CC00;  /* Change this */
}
```

### Connect the contact form
The form currently simulates submission. To make it functional:

**Option A — Formspree (no backend needed):**
```html
<form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option B — EmailJS:**
Replace the `setTimeout` block in the JS with an EmailJS `send()` call.

**Option C — Backend endpoint:**
Use `fetch()` in the form submit handler to POST to your API endpoint.

---

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | 80+     |
| Firefox | 75+     |
| Safari  | 13+     |
| Edge    | 80+     |

Uses: CSS Custom Properties, CSS Grid, CSS Flexbox, IntersectionObserver, `requestAnimationFrame`, `fetch` (not used but available).

---

## 📝 Notes

- The horse-rider logo uses the **🏇** Unicode emoji styled in a lime-green rounded square badge — no external icon library required.
- All JavaScript is vanilla ES6+, wrapped in an IIFE to avoid global scope pollution.
- Images are loaded with `loading="lazy"` for performance.
- The stats counter uses a cubic ease-out function for a natural feel.
- Section alternation (white / off-white / dark) provides visual rhythm without borders.

---

*Built for Prem Pooja Textile Processors Pvt. Ltd. — Mumbai & Badlapur, Maharashtra, India.*
