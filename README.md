# 呈分試試卷搜尋器

Traditional Chinese past-paper searcher for 小五下–小六下 中英數 (234 papers). Self-contained `index.html`.

## Live site

- **GitHub Pages (preferred):** https://windart119.github.io/tsa-searcher/
- CDN mirror (works before Pages is on): https://cdn.jsdelivr.net/gh/windart119/tsa-searcher@main/index.html

## Enable Pages (one-time, if site 404s)

Repo → **Settings** → **Pages** → Build and deployment → Source: **Deploy from a branch** → Branch **main** / **/(root)** → Save.

Or Source: **GitHub Actions** (uses `.github/workflows/pages.yml`).

## Files

- `index.html` — site entry (embedded paper JSON)
- `.nojekyll` — skip Jekyll processing
