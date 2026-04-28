# Easley Labs Signature Assets

Static asset host for email signature images. Deployed to Vercel at `signature.easleylabs.com`.

## Files

- `public/photo.jpg` — headshot
- `public/logo-color.png` — horizontal full color (light backgrounds)
- `public/logo-reverse.png` — horizontal reverse (dark backgrounds)
- `public/logo-stacked-color.png` — stacked full color
- `public/logo-stacked-reverse.png` — stacked reverse

## Deploy

Vercel auto-deploys on push to main. Static files in `public/` are served at the root.

## Cache

Images are cached for 1 year (`max-age=31536000, immutable`). To force refresh, rename the file rather than overwriting.
