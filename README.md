# Dan Belda portfolio deployment

This repository is a plain static site: `index.html` is served from the repository root and needs no framework, package installation, or build command.

## Vercel import settings

- Framework Preset: Other
- Root Directory: `.` (repository root)
- Build Command: leave blank
- Output Directory: `.` or leave blank to serve the root
- Install Command: leave blank

The project slug suggestion is `dan-belda-portfolio`; if available, its URL is `https://dan-belda-portfolio.vercel.app/`. The slug and domain must be claimed in your Vercel account.

Before sharing the Vercel URL, update the canonical URL and Open Graph `og:url`/`og:image` in `index.html` from the current GitHub Pages URLs to the actual Vercel URL. Also update the domain in `robots.txt` and `sitemap.xml` if the chosen Vercel project slug differs.

## Files and image paths

Keep existing images in the repository root alongside `index.html`. The HTML references filenames with spaces and capitalization, so preserve names exactly. No build output or framework-specific `public` directory is required.
