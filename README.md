# Alex's docs site — publish instructions

A plain-HTML docs site (no build step, no dependencies) holding all three
portfolio pieces. This folder is ready to become the "single link" for
applications.

## Contents

- `index.html` — landing page with cards for all three samples
- `quickstart.html` — API quickstart (**content placeholder — see below**)
- `help-article-fetch-single-post.html` — converted from
  `../help-article-fetch-single-post.md`
- `troubleshooting-jsonplaceholder-errors.html` — converted from
  `../troubleshooting-jsonplaceholder-errors.md`
- `styles.css` — shared styles

## Before publishing (main agent)

1. ~~**Fill in the quickstart.**~~ **Done 2026-10-06** — the quickstart page
   was filled in (research-stage fill; original Oct 2 draft text wasn't
   recoverable from goal files, so it was written fresh to the same brief:
   one curl request, what the response means, and what to do when it breaks).
2. **Sanity-check links.** All links are relative (`index.html`,
   `quickstart.html`, `help-article-fetch-single-post.html`,
   `troubleshooting-jsonplaceholder-errors.html`, `styles.css`) so the folder
   works as-is when served. Open `index.html` locally (or ask the user to)
   and click through all cards, nav links, and prev/next links.
3. **Optional:** swap "Alex · Technical Writer" branding and the footer line
   for Alex's full name if he wants it on the page.

## Publish (free, ~10 minutes)

Best fit for the $0–200 plan, and it doubles as Git/GitHub portfolio evidence:

1. Create a GitHub repo named `alexwrites-docs` (or `docs`), set it to **Public**.
2. Copy the entire contents of this folder into the repo root.
3. In repo settings → **Pages** → Deploy from branch → `main` → `/ (root)` → Save.
4. The single application link becomes:
   `https://<github-username>.github.io/<repo-name>/`

That link goes on the resume, LinkedIn, and every application.
