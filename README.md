# Quiet Progress blog

Static blog for the **Focus – Quiet Progress** Facebook page.
Plain HTML + one CSS file. No framework, no build step, no webfonts.

- `index.html` — home, lists all essays
- `<slug>/index.html` — one essay per folder (clean URLs)
- `style.css` — whole design system; light + dark via `prefers-color-scheme`
- `.nojekyll` — serve files as-is, skip Jekyll
- `sitemap.xml`, `robots.txt` — SEO

Live: https://quiet-progress.pages.dev/

## Adding a post
Copy any essay folder, change the slug, then update in the new file:
`<title>`, `meta description`, `canonical`, the three `og:` tags, `h1`, body.
Then add a `<li>` to `index.html` and a `<url>` to `sitemap.xml`.

Every post ends with the Facebook follow card — that is the whole point of the site.
