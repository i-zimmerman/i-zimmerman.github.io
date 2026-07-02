# Alex Zimmerman — personal site

Static one-page resume site, ready for GitHub Pages.

## Deploy to GitHub Pages

1. Create a repo named `i-zimmerman.github.io` (user site) — or any repo name for a project site.
2. Push the contents of this folder to the repo root (branch `main`).
3. Repo → Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Site goes live at `https://i-zimmerman.github.io/` within a minute or two.

## If you use a different URL

Update the URL in these places:
- `index.html`: `<link rel="canonical">`, all `og:*` / `twitter:*` image+url metas, JSON-LD `url` and `image`
- `robots.txt`: Sitemap line
- `sitemap.xml`: `<loc>`

## After deploy

- Submit the site to [Google Search Console](https://search.google.com/search-console) (URL prefix → verify via HTML tag or DNS) and submit `sitemap.xml`.
- Add the site URL to your LinkedIn profile, GitHub profile, and resume header — backlinks help indexing.
