# Imperial Mortgages

A standalone, single-file website for Imperial Mortgages (Dubai). Open `index.html` in a browser or upload it to any static host. It needs no build step.

## Deploy
- **Vercel:** import this repository at vercel.com/new and click Deploy (Framework Preset: Other).
- **Hostinger:** upload `index.html` to `public_html` in hPanel's File Manager.

## SEO and sharing files
- `robots.txt`, `sitemap.xml`, `llms.txt`, `site.webmanifest`
- `og-image.png` (1200×630 social share image), favicons and app icons
- All of these use `https://imperialmortgages.ae`. If your domain is different, find and replace it in `index.html`, `robots.txt`, `sitemap.xml` and `llms.txt`.
- Upload every file in this repository to `public_html`, not only `index.html`.

## Before launch
- Update the indicative rates in the ticker (`.ticker` section).
- Connect the call-back form to your CRM or a form service (see the `TODO` in the script).
- Add your licence or registration details to the footer's legal line.
