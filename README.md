# vocalcord-site

Marketing site for [Vocalcord](https://vocalcord.app) — the iOS app that plays custom sounds when you plug in your charger.

## Structure

Pure static HTML. No build step. No dependencies.

```
/
├── index.html     # Landing page
├── privacy.html   # Privacy policy (required by App Store)
├── support.html   # Support contact (required by App Store)
├── terms.html     # Terms of service
├── icon.png       # App icon used in nav + favicon
└── README.md
```

## Deploy

Deployed via **Cloudflare Pages**, auto-builds on push to `main`.

- **Framework preset:** None
- **Build command:** _(empty)_
- **Build output directory:** `/`

## Local preview

Open `index.html` in a browser, or run any static server:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Domain

`vocalcord.app` — DNS managed via Cloudflare.
