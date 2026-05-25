# TrishaCreates

> Websites that elevate brands.

The official portfolio site for **TrishaCreates** — modern, aesthetic, high-converting
websites for businesses, creators and brands.

## What's inside

A single, hand-crafted, fully responsive `index.html`:

- Soft beige + blush-pink luxury palette
- Premium serif (Cormorant Garamond) + clean sans (DM Sans) pairing
- Hero, About, Services, Featured Projects, Testimonials, Contact, Footer
- Smooth scrolling, scroll-reveal animations, hover micro-interactions
- Mobile menu + responsive layouts down to 480px
- Zero build step, zero dependencies — just open `index.html`

## Run locally

```bash
# any static server works, e.g.
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy for free

This is a single static file, so it can host on almost any free service.

### Option 1 — GitHub Pages (recommended, zero-config)
1. Push to GitHub (already done if you're reading this on GitHub).
2. Repo **Settings -> Pages**.
3. **Source:** `Deploy from a branch` -> Branch: `main` -> Folder: `/ (root)` -> **Save**.
4. Your site will be live at `https://<username>.github.io/trishacreates/` in ~1 minute.

### Option 2 — Netlify Drop
Drag the project folder onto [app.netlify.com/drop](https://app.netlify.com/drop) -> instant URL.

### Option 3 — Vercel
`npm i -g vercel && vercel` from the project root, accept defaults.

### Option 4 — Cloudflare Pages
Connect this GitHub repo at [pages.cloudflare.com](https://pages.cloudflare.com) — no build command needed.

## Customising

All content + styles live in `index.html`. To update:
- **Copy** (headings, services, projects, testimonials): search for the section comments (e.g. `<!-- PROJECTS -->`).
- **Colours**: tweak the CSS variables inside `:root { ... }` near the top.
- **Fonts**: change the Google Fonts `<link>` and the `--serif` / `--sans` variables.
