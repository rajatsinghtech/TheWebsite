> Written manually, without AI assistance.

# TheWebsite

## What this does

Personal website of Rajat Singh â€” contact links, portfolio, and
certifications in plain static HTML/CSS/JS, with no framework and no build
step. Served as [rajatsingh.tech](http://rajatsingh.tech/) via GitHub Pages
(`CNAME`).

## Business process

One page answers "who is Rajat and how do I reach him": identity and photo
up top, experience and certifications in the middle, contact links at the
bottom. Content edits are plain HTML edits â€” nothing to rebuild or redeploy
beyond pushing.

## Technical flow

Static files served as-is: `index.html` pulls styles and scripts from
`assets/`, imagery from `images/`, fonts from Google Fonts. No backend, no
API calls, no trackers.

## Repository structure

- [`index.html`](index.html) â€” the homepage
- [`assets/`](assets/) â€” stylesheets and scripts
- [`images/`](images/) â€” photos and badges
- [`CNAME`](CNAME) â€” custom domain for GitHub Pages
