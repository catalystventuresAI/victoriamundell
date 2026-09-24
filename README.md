# Victoria Mundell — Interior Design Portfolio

Static portfolio site. No build step.

## Structure
- `index.html` — the full site (home, projects, about, contact) with SEO metadata and structured data
- `support.js` — runtime the page needs; keep it next to `index.html`
- `images/` — project drawings, cover images, headshot
- `Victoria-Mundell-Resume.pdf` — linked from "View Resume" on the About page
- `favicon.svg`, `favicon-*.png`, `apple-touch-icon.png` — site icons
- `robots.txt`, `sitemap.xml` — search engine files

## Publish on GitHub Pages
1. Create a repository and upload **everything in this folder** to the root (including `.nojekyll`).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Custom domain: add it under Settings → Pages.

## Before going live
Replace `https://victoriamundell.com` with the real domain in `index.html` (canonical, Open Graph, Twitter and JSON-LD tags), `robots.txt` and `sitemap.xml`.

## Preview locally
Open via a local server (not by double-clicking), e.g. `python3 -m http.server` in this folder, then visit http://localhost:8000.
