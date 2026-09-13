# Portfolio site

Single-page portfolio for Mohamed Zakir Hussain — AI Quality Engineering & Test
Automation Lead. Hand-written HTML with an inline stylesheet: no framework, no npm,
no build step, no Jekyll. Open `index.html` in a browser and that is the whole thing.

```
index.html            the page (content + styles + JSON-LD)
assets/og-image.png   1200x630 link preview card for LinkedIn / X / Slack
assets/favicon.svg
robots.txt            allows everything, points at the sitemap
sitemap.xml
.nojekyll             tells GitHub Pages to serve the files as-is
```

## Publishing

The page's canonical URL, `<link rel="canonical">`, sitemap entry and the absolute
`og:image` URL all point at **`https://iamzakirzr.github.io/`**, so the intended home
is a user-site repo:

1. Create a public repo named exactly `iamzakirzr.github.io`.
2. Copy the contents of this folder into its root (not into a `docs/` subfolder).
3. Push to `main`, then **Settings → Pages → Source: Deploy from a branch →
   `main` / `/ (root)`**.

To serve it from this repo instead, set **Settings → Pages → `main` / `/docs`**. It
then lives at `https://iamzakirzr.github.io/iamzakirzr/`, and four absolute URLs in
`index.html` need that prefix — the canonical link, `og:url`, `og:image` and
`twitter:image` — plus the `<loc>` in `sitemap.xml`. Relative paths (`assets/...`)
work either way.

## Editing

Everything is in `index.html`, in document order: `<head>` metadata, then one
`<style>` block, then the sections (`#about`, `#impact`, `#ai`, `#experience`,
`#work`, `#recognition`, `#contact`). Colours are CSS custom properties on `:root`.
The JSON-LD `Person` block at the bottom mirrors the visible content — update both
when the résumé changes.

The page deliberately omits a phone number and a downloadable résumé PDF; the contact
section uses a `mailto:` with a "Request résumé" subject instead.

## Regenerating the link preview card

`assets/og-image.png` is a screenshot of a small HTML card at 1200x630. Re-render it
with any headless browser at that exact viewport; LinkedIn needs a raster image and
caches aggressively, so validate changes with LinkedIn's Post Inspector afterwards.
