# Scroll Patrol — website

Two static pages, hosted free on GitHub Pages.

| File | Purpose | App Store Connect field |
|---|---|---|
| `index.html` | Marketing / overview | Marketing URL |
| `support.html` | Support FAQ + privacy policy | Support URL |
| `support.html#privacy` | Jumps to the policy | Privacy Policy URL |

Both files are self-contained: all CSS is inline and the screenshots are
embedded as data URIs, so there are no assets to keep in sync. The only
external request either page makes is to Google Fonts.

Editing is just editing the HTML and pushing — GitHub Pages redeploys on
every push to `main`.
