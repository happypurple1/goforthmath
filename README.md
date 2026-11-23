# goforthmath

Static source for **[goforthmath.com](https://goforthmath.com)** — my online mathematics instruction site.

Plain HTML/CSS with no build step. The live site is hosted on Cloudflare; a mirror is also served via GitHub Pages at **https://happypurple1.github.io/goforthmath/**.

## Pages

| File | Page |
|------|------|
| `index.html` | Home |
| `algebra2.html` | Algebra 2 |
| `precalc.html` | Precalculus |
| `research.html` | Research |
| `resources.html` | Resources |
| `contact.html` | Contact |
| `tsi.html` | TSI Study Hall |
| `sine-wheel-lab.html` | Sine Wheel Lab (interactive) |

Classroom materials (PDF) live in `materials/`. Shared styling lives in `styles.css`; `favicon.*` / `apple-touch-icon.png` and `robots.txt` round out the site.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
