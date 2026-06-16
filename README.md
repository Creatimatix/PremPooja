# Prem Pooja Textile Processors Pvt. Ltd. — Website Documentation

A complete multi-page informational website for **Prem Pooja Textile Processors Pvt. Ltd.** Built as self-contained HTML files — no build tools, no npm, no server required.

---

## 📁 File Structure

```
Prem Pooja Textiles/
├── index.html       ← Main website (Lime Green + Black theme)
├── index1.html      ← Alternate design (Navy Blue + Gold theme)
├── fabrics.html     ← Fabric types & detailed services reference page
└── README.md        ← This documentation
```

---

## 🌐 Pages Overview

### 1. `index.html` — Main Website (Lime Green Theme)
The primary website matching the brand's logo colour palette.

**Color Scheme**
| Variable | Value | Usage |
|---|---|---|
| Primary | `#B5CC00` | Lime green — brand primary |
| Dark | `#1A1A1A` | Near-black — backgrounds, text |
| White | `#FFFFFF` | Light sections |
| Off-White | `#F5F5F5` | Alternating sections |

**Fonts:** Montserrat (headings) + Open Sans (body) — Google Fonts

**Sections:**
1. Sticky Navbar — transparent over hero, white on scroll, hamburger mobile menu
2. Hero — full-viewport textile background, tagline, dual CTA, stats bar
3. About — company story, 25+ year badge, mission/vision/quality/sustainability cards
4. Services — 6 cards (Bleaching, Dyeing, Printing, Finishing, Fabric Processing, Quality Testing)
5. Why Choose Us — animated stats counters + 6 differentiator cards (dark section)
6. Process — 5-step connected timeline workflow
7. Gallery — CSS grid with 6 Unsplash textile images + hover overlays
8. Industries — 5 industry sectors served
9. Testimonials — 3 client reviews with star ratings
10. Contact — 2 branch cards + contact form with validation
11. Footer — 4-column layout, social icons, quick links

---

### 2. `index1.html` — Alternate Design (Navy Blue + Gold Theme)
A classic, prestigious alternative design — same content, entirely different aesthetic.

**Color Scheme**
| Variable | Value | Usage |
|---|---|---|
| Navy | `#0D1B2A` | Deep navy — primary background |
| Navy 2 | `#162235` | Card backgrounds |
| Gold | `#C9A84C` | Accent — buttons, lines, labels |
| Gold Light | `#E8C97A` | Hover states |
| Cream | `#FAF6EE` | Light section backgrounds |
| Cream 2 | `#F2EBD9` | Alternating light sections |

**Fonts:** Playfair Display (headings) + Lato (body) + Cormorant Garamond (hero subtitle) — Google Fonts

**Design Highlights:**
- Diamond ornament dividers between section headers
- Hexagonal logo crest (clip-path polygon)
- Underline slide animation on nav links
- Gold accent ribbon at hero bottom (replacing stats bar)
- Stacked image layout in About with inset accent photo
- Dark navy service grid with number watermarks
- Sliding image panel in Why Us section with quote overlay
- Bordered service cards with gold bottom highlight
- Square avatar initials for testimonials

**Sections:** Same content structure as `index.html` with the additions of:
- Dedicated stats band (`#stats`) between Why Us and Process
- Links to `fabrics.html` in nav and footer

---

### 3. `fabrics.html` — Fabric Types & Service Details
A rich reference page for clients to understand what fabrics are processed and how each service works.

**Color Scheme:** Combined Navy + Lime Green — bridging both themes for a cohesive sub-page.

**Sections:**

| Section | Description |
|---|---|
| Page Hero | Dark navy banner with breadcrumb, page title, tag pills for fabric types |
| Fabric Types | 9 fabric cards with filter buttons (All / Natural / Synthetic / Blend / Specialty) |
| Service Details | 4 expanded service cards with feature checklists and compatible fabric tags |
| Processing Explained | Tabbed interface — step-by-step breakdown for each service |
| Fabric × Service Matrix | Full comparison table — which services work with which fabrics |
| Processing Capacity | 4 callout blocks (daily throughput, colour range, turnaround, MOQ) |
| CTA Banner | Lime green call-to-action linking back to contact and services |
| Footer | Compact footer matching the lime green theme |

**Fabric Types Covered:**
1. Cotton (Natural)
2. Polyester (Synthetic)
3. Silk (Natural)
4. Viscose / Rayon (Semi-synthetic)
5. Linen (Natural)
6. Polyester-Cotton Blend (Blend)
7. Nylon / Polyamide (Synthetic)
8. Wool & Wool Blends (Blend)
9. Technical & Industrial Fabrics (Specialty)

**Service Detail Cards:**
- Bleaching — process notes, eco-compliance, compatible fabrics
- Dyeing — dye systems, colour-matching specs, capacity
- Printing — screen / rotary / digital, paste types, fastness
- Finishing — mechanical and chemical options, shrinkage specs

---

## 🔗 Page Navigation

All pages are cross-linked:

| From | To | Via |
|---|---|---|
| `index.html` | `index1.html` | (open directly) |
| `index.html` | `fabrics.html` | "Fabrics" nav link |
| `index1.html` | `fabrics.html` | "Fabrics" nav link |
| `fabrics.html` | `index.html` | Logo link + all nav links |

---

## 🏢 Company Details

| Field | Value |
|---|---|
| Company | Prem Pooja Textile Processors Pvt. Ltd. |
| Tagline | Specialist in Bleaching, Dyeing & Printing |
| Founded | 1998 |
| Phone 1 | +91 98195 70709 |
| Phone 2 | +91 98202 80057 |
| Email | prempoojatex@hotmail.com |
| Mumbai Branch | Plot No. 45, MIDC Industrial Area, Andheri East, Mumbai – 400093 |
| Badlapur Branch | Gala No. 12, Badlapur Industrial Estate, Badlapur (W), Thane – 421503 |

---

## ⚡ Features (All Pages)

- Sticky navbar with transparent-to-solid scroll transition
- Active section highlighting in navbar
- Hamburger menu for mobile (animated, accessible)
- Smooth scroll with 78–80px navbar offset
- IntersectionObserver fade-in animations on all sections
- Animated stat counters (index.html & index1.html)
- Scroll-to-top button
- Contact form with client-side validation + success state
- `loading="lazy"` on all images for performance
- Semantic HTML5 with ARIA attributes
- Fully responsive — desktop, tablet, mobile
- Zero npm / build dependencies — open directly in browser

---

## 🖼️ Images

All images from [Unsplash](https://unsplash.com) (free license):

| Photo ID | Usage |
|---|---|
| `photo-1558618666-fcd25c85cd64` | Hero background, gallery dyeing |
| `photo-1586201375761-83865001e31c` | About section, mill operations |
| `photo-1558769132-cb1aea458c5e` | Colourful fabrics, gallery |
| `photo-1620799140408-edc6dcb6d633` | Cotton processing, Why Us |
| `photo-1607082348824-0a96f2a4b9da` | Printing, gallery |
| `photo-1559056199-641a0ac8b55e` | Quality testing, gallery |
| `photo-1558618047-3c8c76ca7d13` | Silk fabric |

---

## 🚀 Deployment

### Open locally
```bash
open index.html
# or
open index1.html
# or
open fabrics.html
```

### Local server (optional)
```bash
python3 -m http.server 8080
# Visit: http://localhost:8080
```

### Deploy (static hosting)
Upload all `.html` files to any static host:
- **Netlify** — drag and drop the folder
- **GitHub Pages** — push to a repo, enable Pages
- **Vercel** — `vercel deploy`
- **cPanel / FTP** — upload files to `public_html/`

---

## 🔧 Customisation

### Change primary colour (index.html)
```css
/* In <style>, update :root */
--lime: #B5CC00;  /* change to your preferred colour */
```

### Change gold accent (index1.html)
```css
--gold: #C9A84C;  /* change to preferred gold tone */
```

### Connect the contact form
Replace the `setTimeout` simulation in the `<script>` block with:

**Formspree (easiest — no backend):**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**EmailJS:**
```js
emailjs.send('service_id', 'template_id', formData);
```

### Add/remove fabric types (fabrics.html)
Each fabric is an `<article class="fabric-card" data-category="...">` element inside `#fabricsGrid`. Add a `data-category` matching one of: `natural`, `synthetic`, `blend`, `specialty`.

---

## 📱 Browser Support

Chrome 80+, Firefox 75+, Safari 13+, Edge 80+

---

*Built for Prem Pooja Textile Processors Pvt. Ltd. — Mumbai & Badlapur, Maharashtra, India.*
