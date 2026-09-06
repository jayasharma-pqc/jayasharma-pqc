# jayasharma-pqc.github.io

Personal academic website for Jaya Sharma — PhD student in Cybersecurity
Engineering at the Technical University of Denmark (DTU Cryptography Group).

Static HTML/CSS, no build step. Served via GitHub Pages.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Home — research, news, CV, contact |
| `publications.html` | Publications and preprints |
| `style.css` | Shared stylesheet |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll) |

## Local preview

Open `index.html` in a browser, or run a static server:

```bash
python -m http.server 8000
```

then visit <http://localhost:8000>.

## Deploy

Push to `main`. In the repo's **Settings → Pages**, set the source to
**Deploy from a branch**, branch `main`, folder `/ (root)`.
