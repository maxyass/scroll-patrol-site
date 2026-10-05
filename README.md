# Scroll Patrol — website

Two static pages, deployed from this repo by Cloudflare Pages.

| File | Purpose | App Store Connect field |
|---|---|---|
| `index.html` | Marketing / overview | Marketing URL |
| `support.html` | Support FAQ + privacy policy | Support URL |
| `support.html#privacy` | Jumps to the policy | Privacy Policy URL |

Both files are self-contained: all CSS is inline and the screenshots are
embedded as data URIs, so there are no assets to keep in sync. The only
external request either page makes is to Google Fonts.

## Deploying

Cloudflare Pages builds on every push to `main`. There is no build step —
framework preset "None", no build command, output directory `/`. Editing a
page is editing the HTML and pushing.
