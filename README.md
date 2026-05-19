# Jackson Heights & Elmhurst Food Crawl

A learning project — single-page food crawl guide for the First Annual Jackson Heights & Elmhurst Food Crawl, May 16 2026.

**Stack**
- **Netlify** — static hosting, auto-deploys from this repo
- **Supabase** — Postgres for stops + ratings, accessed from the browser with Row Level Security

**Files**
- `index.html` — the entire site: HTML, CSS, JS in one file. Pulls stops and ratings from Supabase on load.

Updates to `main` auto-deploy to https://jackson-heights-food-crawl.netlify.app
