# goldenzuoft.ca

Source for the Golden Z @ UofT website. Plain HTML/CSS, no build step —
hosted free on GitHub Pages.

## Structure

- `index.html`, `about.html`, `departments.html`, `podcast.html`, `contact.html` — the site's five pages
- `css/style.css` — all styling and design tokens (colors, type, spacing) at the top of the file
- `js/main.js` — the mobile menu toggle, the only script on the site
- `favicon.svg` — the browser tab icon
- `CNAME` — tells GitHub Pages this repo should serve `goldenzuoft.ca`

## Editing content

Each page is self-contained HTML — open it and edit the text directly.
The header and footer are repeated at the top and bottom of every page,
so a navigation change needs to be made in all five files.

## Before this looks fully live, still to do

- Set up a free Formspree account and drop the form ID into `contact.html` (see the comment above the `<form>` tag)
- Point the Instagram, LinkedIn, and podcast platform links at the real accounts once they exist
- Add the real listen link for Episode 1 once it's published

## Hosting

This repo is served through GitHub Pages, with DNS pointed here from the
domain's registrar. If a future exec needs to move hosting, the site is
just these files — copy them anywhere that serves static HTML.
