# Mechanical Engineer Portfolio

A premium single-page portfolio built for a mechanical (MEP & BIM) engineer, delivered as a client project.

**Live site:** https://waficportfolio.vercel.app

## Overview

The client needed one page that presents engineering experience, MEP and BIM project work, and a direct way for recruiters and contractors to get in touch — fast to load on a phone, and credible enough to send to a hiring manager. Designed, built and deployed end to end.

## Features

- Six responsive sections: intro, about, skills, projects, experience and contact
- Animated section transitions built with Framer Motion
- Six MEP drawing projects presented with detail views
- Contact form routed directly to the client's inbox
- Fully responsive down to small mobile widths
- Deployed on Vercel with continuous deployment from `main`

## Tech stack

| Layer | Tools |
| --- | --- |
| Framework | React 18 |
| Build | Vite |
| Styling | Tailwind CSS |
| Animation | Framer Motion |
| Hosting | Vercel |

## Performance

Performance was a requirement, not an afterthought — the audience opens links on mobile, often on slow connections.

| Metric | Result |
| --- | --- |
| Lighthouse Performance | 90+ |
| Lighthouse SEO | 100 |
| Lighthouse Accessibility | 100 |
| Image payload | ~70% smaller after WebP conversion |

Converting all project imagery to WebP and sizing each image for its display width was the single biggest contributor to the score.

## Running locally

```bash
git clone https://github.com/lianajomaa/mechanical-engineer-portfolio.git
cd mechanical-engineer-portfolio
npm install
npm run dev
```

The dev server runs on `http://localhost:5173`.

```bash
npm run build     # production build
npm run preview   # preview the production build locally
```

## Contact

Built by **Liana Zouher Jomaa** — [GitHub](https://github.com/lianajomaa) · lianajomaa95@gmail.com
