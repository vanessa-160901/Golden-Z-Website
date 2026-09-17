# goldenzuoft.ca

Source for the Golden Z @ UofT website. Plain HTML/CSS.

## Structure

- `index.html`, `about.html`, `team.html`, `departments.html`, `podcast.html`, `contact.html` — the site's six pages
- `css/style.css` — all styling and design tokens (colors, type, spacing) at the top of the file
- `js/main.js` — the mobile menu toggle, the only script on the site
- `images/golden-z-logo.png` — the club logo, background removed
- `favicon.svg` — the browser tab icon
- `CNAME` — tells GitHub Pages this repo should serve `goldenzuoft.ca`

## Page map

The nav bar has an "About" dropdown (hover on desktop, always expanded on
mobile) with two pages under it:

- `about.html` — "Our Story": chartering, mission, what we're building toward
- `team.html` — "Our Team": leadership grid + department breakdown

`departments.html` is still the "What We Do" nav link, but its content is
now the club's ongoing initiatives (birthing kit drives, bake sales, care
packages) rather than departments — those moved to `team.html`.

## Editing content

Each page is self-contained HTML — open it and edit the text directly.
The header and footer are repeated at the top and bottom of every page,
so a navigation or logo change needs to be made in all six files.

## Before this looks fully live, still to do

- On `contact.html`: replace the two `#` links under "Join Golden Z" with your real application form URLs (e.g. Google Forms) — see the comment above them in the source
- On `team.html`: swap the six initial-circle placeholders for real headshots once you have them (each is a small inline `<svg>` — replace it with an `<img>` tag; there's a comment above the first one showing where)
- Point the Instagram, LinkedIn, and podcast platform links at the real accounts once they exist
- Add the real listen link for Episode 1 once it's published

## Hosting

This repo is served through GitHub Pages, with DNS pointed here from the
domain's registrar. If a future exec needs to move hosting, the site is
just these files — copy them anywhere that serves static HTML.
