# charlcye.ai

Source for [charlcye.ai](https://charlcye.ai) — a single-page site
for [Charlcye Mitchell](https://linkedin.com/in/camitchell).

Static HTML + CSS. No build step. Deploys to Cloudflare Pages.

## Local preview

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open `http://localhost:8000`.

## Deploy

Wired to Cloudflare Pages, connected to the `main` branch of this repo.
Every push to `main` triggers a deploy at
[pages.dev](https://dash.cloudflare.com/) and updates `charlcye.ai`.

## Structure

- `index.html` — the entire site
- `styles.css` — one stylesheet
- `favicon.svg` — inline SVG favicon
- `_redirects` — Cloudflare Pages redirect rules (currently just `www` → apex)

## Contact

- LinkedIn: [linkedin.com/in/camitchell](https://linkedin.com/in/camitchell)
- Email: [hi@charlcye.ai](mailto:hi@charlcye.ai)
