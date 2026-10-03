# Milaholz Art — milaholzart.de

Source files for the Milaholz Art website, deployed via Cloudflare Pages.

## Structure
- `index.html`, `agb.html`, `impressum.html`, `datenschutz.html` — site pages
- `assets/` — scroll animation frame sequences (desktop + mobile)
- `images/` — product and gallery images
- `_headers` — Cloudflare Pages security headers config
- `robots.txt`, `sitemap.xml` — SEO config

## Deploying via GitHub + Cloudflare Pages
1. Push this repo to a new GitHub repository.
2. In Cloudflare Pages, connect the GitHub repo (Workers & Pages → Create → Pages → Connect to Git).
3. Build settings: no build command needed (static site), output directory: `/` (root).
4. Keep the custom domain `milaholzart.de` connected under Custom domains.
