# SabeloTech

**Refurb. Reimagined.**

A multi-page website for a fictional second-hand electronics business — selling tested, certified refurbished smartphones, laptops, hard drives, and RAM. Built with plain HTML, CSS, and JavaScript (no frameworks, no build tools).

[Live Site](#) — *replace with your GitHub Pages link once deployed*

---

## Overview

SabeloTech is a front-end portfolio project demonstrating a complete, multi-page business website: a home page, a filterable product catalog, an about/story page, and a working contact form connected to a real backend (Formspree).

The design uses a dark, cyberpunk-inspired aesthetic — near-black backgrounds, neon mint and magenta accents, Orbitron for headings, and JetBrains Mono for body text.

---

## Pages

| File | Purpose |
|---|---|
| `index.html` | Home page — hero section, category preview, trust/promise strip |
| `products.html` | Full product catalog with a working category filter (Phones, Laptops, Hard Drives, RAM) |
| `about.html` | Company story, values, and the device inspection process |
| `contact.html` | Contact details and a live contact form (submits via Formspree) |
| `style.css` | Shared stylesheet — colors, typography, nav, footer, and reusable components |
| `main.js` | Shared JavaScript — scroll-reveal animations and nav hide-on-scroll behavior |

---

## Features

- Fully responsive layout (desktop, tablet, and mobile breakpoints)
- Scroll-triggered fade-in animations using `IntersectionObserver` (no animation libraries)
- Category filtering on the products page, written in vanilla JavaScript
- A real working contact form — submissions are sent via [Formspree](https://formspree.io) and delivered straight to email, with spam protection via a honeypot field
- Consistent design system shared across all pages through a single `style.css`

---

## Tech Stack

- HTML5
- CSS3 (custom properties / CSS variables for theming, CSS Grid and Flexbox for layout)
- Vanilla JavaScript (no frameworks or libraries)
- [Formspree](https://formspree.io) for contact form handling
- Fonts: [Orbitron](https://fonts.google.com/specimen/Orbitron) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

---

## Running Locally

No build step is required. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/SabeloTech123/sabelotech-website.git
cd sabelotech-website
```

Then open `index.html` in your browser, or run a simple local server:

```bash
python3 -m http.server
```

and visit `http://localhost:8000`.

---

## Deployment

This site is deployed using **GitHub Pages**.

1. Push all files to the `main` branch.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. GitHub will publish the site at `https://<username>.github.io/<repo-name>/`.

---

## Project Structure

```
sabelotech-website/
├── index.html
├── products.html
├── about.html
├── contact.html
├── style.css
├── main.js
└── README.md
```

---

## Contact

Built by **Sabelo Maseko**
Email: sabelomaseko09@gmail.com
GitHub: [github.com/SabeloTech123](https://github.com/SabeloTech123)

---

## License

This project is open for educational and portfolio reference. Not a real commercial business.
