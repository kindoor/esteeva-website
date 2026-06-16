# Esteeva website

Static website for Esteeva, hosted on GitHub Pages with the custom domain **esteeva.com**.

## Editing

Everything is in `index.html` (HTML + CSS + a little JS, single file). Edit the text in the
`[...]` placeholders and the colors in the `:root { ... }` CSS block at the top.

- `index.html` — the site
- `404.html` — not-found page
- `CNAME` — tells GitHub Pages the custom domain is `esteeva.com` (do not delete)

## Publishing

This repo is published via **GitHub Pages** (Settings → Pages). Any push to the default
branch redeploys the site automatically within a minute or two.

## Local preview

Just open `index.html` in a browser, or run a tiny local server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```
