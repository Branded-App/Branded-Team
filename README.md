# Branded App — Cover Page

Static, single-file marketing/landing page for **Branded App** (the sports
recruiting platform). Self-contained HTML with inline CSS + a small vanilla-JS
script and base64-embedded images. No build step, no dependencies.

The page links out to the live app at **https://thebrandedapp.com**.

## Deploy (Vercel)

This is a pure static site — `index.html` is served at the root.

1. Push this repo to GitHub.
2. Import it on [vercel.com/new](https://vercel.com/new).
3. Settings:
   - **Framework Preset:** Other
   - **Build Command:** _(leave empty)_
   - **Output Directory:** `.` (root)
4. Attach a domain (e.g. a marketing subdomain) once deployed.

Or deploy straight from this folder with the CLI: `vercel`.

## Edit

Everything lives in `index.html`. To swap the team/partner photos for real
image files later, replace the base64 `data:` URIs with `<img src="...">`
paths and add `loading="lazy"`.
