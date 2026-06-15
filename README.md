# perezofir83.github.io

Personal portfolio & landing page for **Ofir Pérez Weinberg** — founder-operator, builder, and growth entrepreneur.

A single-page site that tells the cross-functional story (business development, sales, marketing, strategy, product, engineering) and showcases selected ventures as case studies.

## Live

→ https://perezofir83.github.io

## Stack

Pure static site — no build step. Just `index.html`, `styles.css`, `script.js`. Served directly by GitHub Pages.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

- `index.html` — all content & sections (hero, story, capabilities, case studies, ventures, contact)
- `styles.css` — design system (dark editorial theme, Fraunces + Inter)
- `script.js` — nav scroll state + scroll-reveal animations

## Editing

Content is plain HTML — edit the relevant `<section>` in `index.html`. Colors and type live as CSS variables at the top of `styles.css`.

---

© Ofir Pérez Weinberg
