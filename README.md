# stint.uz

Marketing site and legal pages for **Stint** — a native iOS planner for people who work shifts.

Static HTML/CSS, no build step. Deployed on Cloudflare Pages.

| Page | File |
|------|------|
| Landing | `index.html` |
| Privacy Policy | `privacy.html` → served at `/privacy` |
| Terms of Use | `terms.html` → served at `/terms` |

Screenshots in `img/` are real captures from the app.

## Deploy

Cloudflare Pages, connected to this repo:
- **Framework preset:** None
- **Build command:** *(empty)*
- **Build output directory:** `/`

Cloudflare Pages serves `/privacy` and `/terms` from the `.html` files automatically
(clean URLs), which is what the app's in-app links point to.
