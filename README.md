# AP-OWO website

The landing page for AP-OWO — plain HTML/CSS/JS, no build step. Hosted on
GitHub Pages.

## Publish on GitHub Pages

1. Create a public GitHub repo named **`ap-owo`** (under `Sterin32Saji`).
2. Push this repository as-is; `index.html` and the site assets are already at the root.
3. Repo → **Settings → Pages** → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
4. In a minute or two the site is live at **https://sterin32saji.github.io/ap-owo/**.

If you use a different repo name or a custom domain, replace
`https://sterin32saji.github.io/ap-owo/` in `index.html` (canonical, og:url,
og:image, twitter:image — social previews need the full address).

## Privacy policy

`privacy.html` is the current policy. You can use
`https://sterin32saji.github.io/ap-owo/privacy.html` as the privacy-policy URL
in Play Console.

## What's here

- `index.html` — the page (all CSS and JS inline)
- `assets/video/` — web-sized promo videos (H.264, fast start)
- `assets/img/` — WebP screenshots, video posters, icons, `og.png` (1200×630 share image)
- `assets/fonts/` — Space Grotesk (SIL Open Font License, see OFL-SpaceGrotesk.txt)
- `.nojekyll` — tells GitHub Pages to serve files as-is

Videos and screenshots come from `marketing/`; regenerate there and copy over
if the app's look changes.

The policy text is also kept in [`PRIVACY-POLICY.md`](PRIVACY-POLICY.md).
