# Youktik Sajjan — Minimal Craft Portfolio

**ysdvision.github.io**

Minimalistic dark portfolio inspired by Minecraft 1.20+ deepslate + emerald aesthetic, blended with futuristic UI minimalism.

## Pages

- **About** — Bio, philosophy, currently-at
- **Projects** — Card grid with GitHub links
- **Cultural** — Vertical timeline of activities
- **Music** — Spotify embeds + album grid
- **CV** — Live-synced CV via iframe (updates when `cv.html` changes)

## Tech Stack

- HTML + CSS (custom, no framework)
- Google Fonts: Press Start 2P + Inter
- Font Awesome 6.5 icons
- AOS (Animate On Scroll) library
- Spotify Embed iFrames

## Design System

| Token | Value |
|---|---|
| Background | `#0f1115` |
| Surface | `#1a1d24` |
| Card | `#222630` |
| Accent (Emerald) | `#3acb7a` |
| Glow | `rgba(58,203,122,0.4)` |
| Text Primary | `#f2f2f2` |
| Text Secondary | `#a0a7b5` |

## CV Sync

The portfolio embeds `cv.html` via iframe. To update the CV on the website:

1. Edit your CV source file
2. Export/convert to HTML
3. Replace `cv.html` in this repository
4. Push — the site auto-updates

## Deployment

1. Create a **public** repository named `ysdvision.github.io`
2. Copy all files from this `portfolio/` folder to the repo root
3. Push to `main` branch
4. GitHub Pages auto-deploys at: https://ysdvision.github.io

```bash
git init
git add .
git commit -m "Initial portfolio deploy"
git branch -M main
git remote add origin https://github.com/ysdvision/ysdvision.github.io.git
git push -u origin main
```

## Spotify Integration

Currently using embed iframes. For live data:

1. Register at [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
2. Use OAuth 2.0 Authorization Code Flow
3. Endpoints:
   - Recently Played: `GET /v1/me/player/recently-played`
   - Top Artists: `GET /v1/me/top/artists`
   - Top Tracks: `GET /v1/me/top/tracks`

## License

© 2026 Youktik Sajjan. All rights reserved.
