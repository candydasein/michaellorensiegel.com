# michaellorensiegel.com

Personal site for Michael Loren Siegel. Static HTML, no build step.

**Live:** https://michaellorensiegel.com

## Structure

- `website/` — site root, served as-is. Add new files here.
  - `website/index.html` — single-page resume + bio.

## Deploy

Cloudflare Pages, auto-deploys on push to `main`.

- **Build command:** _(none)_
- **Build output directory:** `website`

Edit `website/index.html`, commit, push. Live in ~30 seconds.

## To do

- Add `website/cv.pdf` and reattach the download link in the header and footer of `index.html`.
