# Huffines Wood Products

## Stack
- **HTMX 1.9.12** — handles all page navigation. Nav links swap fragments into `#content` without a full page reload.
- **Formspree** — handles order form submissions. No backend needed.
- **Cloudflare Pages** — static hosting, deployed from the `master` branch on GitHub.
- **No other frameworks** — everything else is vanilla HTML, CSS, and JS.

---

## File structure
All serving files live in `public/`. Cloudflare Pages must point to `public/` as the root.

---
