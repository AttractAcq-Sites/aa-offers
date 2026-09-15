# Attract Acquisition — website

Managed by AA Console. Pages are published here from the Conversion tab; the
sales agent widget is loaded from https://runtime.attractacq.com and
configured per page.

Do not hand-edit published pages — the next publish overwrites them.

Layout:

- `index.html` — homepage
- `<page-slug>/index.html` — one directory per published page
- `assets/` — shared files
- `aa/config.json` — non-secret site identity
- `.nojekyll` — keeps GitHub Pages from running generated HTML through Jekyll

Nothing secret belongs in this repository. It is served publicly.
