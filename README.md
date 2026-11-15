# yz.dev — Yian Zhuang's Portfolio

Personal portfolio for Yian Zhuang — Computer Engineering @ UC San Diego.

## Local development

No build step required. Serve the root directory with any static file server:

```bash
# Option 1 — Python (built-in)
python3 -m http.server 8080

# Option 2 — VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Option 3 — Node.js
npx serve .
```

Then open http://localhost:8080.

## Before publishing

- [ ] Fill in your GitHub repo URLs in `index.html` (search for `TODO:repo`)
- [ ] Drop `resume.pdf` in the repo root
- [ ] Uncomment the "Currently building" line in `index.html` and fill it in
- [ ] Fill in real metrics for each project (search for `TODO:` in `index.html`)
- [ ] Replace `TODO-your-domain` in `robots.txt` and `sitemap.xml`
- [ ] Add `og:url` and `og:image` meta tag values in `index.html`
- [ ] Create a 1200×630 `og-image.png` for social preview cards
- [ ] Add `favicon.ico` (32×32) and `apple-touch-icon.png` (180×180)

## Deployment

Recommended: **Vercel** (zero-config, HTTPS by default, auto-deploy on push).

```bash
# Push to GitHub first
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/YianDZh/YianDZh.github.io.git
git push -u origin main

# Then connect the repo at vercel.com — no config needed for plain HTML/CSS/JS
```

## Live URL

TODO: add deployed URL here once live.

See `TODO.md` for stretch-goal features.
