# OneTechGirl — Website

The OneTechGirl marketing site. AI, made simple.

## Structure
- `index.html` — redirects to the homepage
- `site/index.html` — the homepage
- `styles.css` + `tokens/` — design system (Space Grotesk, ink/paper/lime/coral)
- `assets/` — logo, photos, fonts

## Run locally
Open `site/index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## GitHub Pages
Settings → Pages → Deploy from branch → `main` / root. The root `index.html` forwards to `site/index.html`.
