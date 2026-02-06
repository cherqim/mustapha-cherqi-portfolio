# Mustapha Cherqi — Portfolio

[![Live Site](https://img.shields.io/badge/Live%20Site-cherqi.me-00e5cc)](https://cherqi.me)
[![GitHub](https://img.shields.io/badge/GitHub-cherqim-0c0c0c)](https://github.com/cherqim)

Personal portfolio for **Mustapha Cherqi**, full-stack developer. Showcases projects, stack, and contact.

## Live

**https://cherqi.me**

## Stack

- Single HTML file (no build step)
- Vanilla CSS with custom properties
- Vanilla JS (scroll progress, reveal animations, mobile nav)
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) (display), [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body)

## Features

- **Hero** — Name-first layout, availability badge, terminal-style line, key stats
- **Scroll progress** — Top bar reflects page scroll
- **Reveal on scroll** — Sections and cards animate into view
- **Responsive** — Mobile menu, stacked layouts, touch-friendly
- **Accessibility** — Focus states, `aria` on menu toggle, reduced-motion respected
- **Dark theme** — Deep background with teal/cyan accent

## Sections

- **About** — Identity, location, three “roles” (Developer, Architect, Seeker)
- **Projects** — Morokeys Backoffice, AR Services Foundation, RentalApp V2
- **Skills** — Frontend, Mobile, Backend, Auth & Payments, Data & State, Design & SEO
- **Contact** — Email, GitHub, Telegram

## Local

```bash
git clone https://github.com/cherqim/mustapha-cherqi-portfolio.git
cd mustapha-cherqi-portfolio

# Serve
python3 -m http.server 8000
# or
npx serve .
```

## Deploy

Static site; works with any host (Vercel, Netlify, Caddy on VPS, etc.).

---

Built by Mustapha Cherqi.
