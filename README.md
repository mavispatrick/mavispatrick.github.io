# Mavis Garth Patrick — Portfolio

Personal portfolio site for **Mavis Garth Patrick**, Artificial Intelligence Analyst.

**Live site:** https://mavispatrick.github.io/

## Stack

Static site — no build step required.

| File | Purpose |
| --- | --- |
| `index.html` | Page structure and content |
| `styles.css` | Dark teal/cyan glassmorphism design system, responsive layout |
| `script.js` | Scroll-reveal animations, mobile nav toggle, active section highlighting |
| `assets/favicon.svg` | Site icon |
| `documents/Mavis_Garth_Patrick_CV.pdf` | Downloadable CV |

## Design

Adapted from a clean dark portfolio aesthetic:

- **Colors** — deep navy base (`#070a12` → `#0b1220`) with teal/cyan accents (`#2dd4bf`, `#7dd3fc`)
- **Type** — Space Grotesk for headings, IBM Plex Sans for body
- **Layout** — sticky blurred header, hero with stat strip, 3-column project grid, two-column skills grid, timeline for experience and education, certification cards, contact panel
- **Motion** — IntersectionObserver scroll-reveal, card hover lift, active nav highlighting
- **Responsive** — 3 → 2 → 1 column, hamburger navigation below 620px, `prefers-reduced-motion` respected

## Content

All content is sourced from the CV:

- 4 featured projects (DeutschConnect, PolySignal, Fashion Fusion, P&L Dashboard)
- 6 skill categories
- 5 professional roles, 2 degrees
- 7 certifications
- Contact: email, phone, and CV download

## Deploying

Serves directly from the `main` branch via GitHub Pages. To publish changes, push to `main`
and the site rebuilds automatically.

## Notes

- Social/profile buttons are intentionally omitted; only in-page navigation, email, phone, and the CV download are present.
- The hero uses an initials avatar (`MGP`) as a placeholder. To use a portrait, drop an image at `assets/profile.jpg` and replace the `.avatar-initials` `<div>` in `index.html` with an `<img class="avatar">` tag.
