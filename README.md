# CIRCARB website — first design draft

A responsive, static website for the CIRCARB EPSRC research programme. The site is deliberately written in plain HTML, CSS and JavaScript without a framework, making it straightforward to host on GitHub Pages and update later.

## Site navigation
Home, About, Research, Applications, People & Partners, Impact & Resources, News & Events, Work with CIRCARB.

Each section has its own direct URL using a hash route such as `/#/research`, which works with GitHub Pages without server-side routing.

## Running locally
Open `index.html` in a modern browser, or serve the repository folder using `python -m http.server 8000`.

## Publish
In the repository, open **Settings → Pages**, set **Deploy from a branch**, choose **main** and **/(root)**, then save. Your site should be available at `https://drimran357.github.io/circarb/` once GitHub Pages completes publishing. This is a proposed URL, not a verified live deployment.

## Editing
- `site.js`: page text, navigation, research cards, team examples and diagrams.
- `styles.css`: site appearance, colour variables and responsive layouts.
- `index.html`: page metadata and loading.

## Important
This is an illustrative first draft. Sample projects, impact figures, activities and role descriptions are placeholders; verify all CIRCARB programme claims before public launch. Partner logos and formal funding acknowledgements must be checked and approved before release. The enquiry form currently opens the user's email client and does not store or transmit enquiries to a backend.

Designed for future extension with real partner identities, work packages, demonstrators, publications, news, accessibility review and impact data.
