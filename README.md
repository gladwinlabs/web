# Gladwin Labs website

Source for [gladwinlabs.com](https://gladwinlabs.com), the Gladwin Labs company website.

Static HTML, no build step. Open `index.html` in a browser or serve the folder from any static host.

## Layout

- `index.html` - the landing page (markup, styles and scripts in one file)
- `404.html` - not-found page, picked up automatically by GitHub Pages
- `assets/` - logo, favicons, self-hosted fonts and the Open Graph share image
- `manifest.webmanifest` - icons and colours for add-to-home-screen
- `robots.txt`, `sitemap.xml` - search engine files, served from the site root
- `CNAME`, `.nojekyll` - GitHub Pages configuration

## Deploying with GitHub Pages

1. In the repo settings, open Pages and set the source to the `main` branch, root folder.
2. Point the domain's DNS at GitHub Pages (A records for the apex and a CNAME for `www`).
3. Once DNS resolves, tick "Enforce HTTPS" in the Pages settings.

The `CNAME` file already contains `gladwinlabs.com`, so the custom domain is picked up on the first deploy.
