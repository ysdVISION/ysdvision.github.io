# ⬡ Youktik Sajjan — The End Dimension Portfolio

**ysdvision.github.io**

A Minecraft End-dimension themed developer portfolio. Void black backgrounds, chorus plant accents, floating endstone islands, and pixel-perfect block geometry — rendered as a systems architect's mind palace.

## Sections

- **About** — Hero, bio, Minecraft-style tooltip panel, philosophy quote
- **Projects** — 6-card grid with hover glow + left-border reveal
- **Culture** — Floating island timeline with chorus plant accents
- **Music** — Jukebox-style panel, disc slots, Spotify embeds
- **Blog** — Book & quill log entries (placeholder posts)
- **Ventures** — Dragon Egg section with stage-tagged venture cards
- **Contact** — End Gateway portal animation + contact form

## Design System

| Token | Value |
|---|---|
| Void Deepest | `#050508` |
| Void Base | `#0a0b12` |
| Void Surface | `#0f1020` |
| Endstone Bright | `#d4cfa8` |
| Chorus Bloom | `#c084fc` |
| Chorus Pale | `#e9d5ff` |
| Portal Cyan | `#67e8f9` (one CTA only) |

## Typography

| Tier | Font | Usage |
|---|---|---|
| 1 | Press Start 2P | Hero name, nav logo |
| 2 | VT323 | Section headers, card titles |
| 3 | Share Tech Mono | Labels, tags, nav links |
| 4 | Nunito | Body copy |

## Tech Stack

- HTML + Tailwind CDN + Vanilla JS
- Google Fonts (Press Start 2P, VT323, Share Tech Mono, Nunito)
- CSS custom properties for full color system
- IntersectionObserver scroll animations
- 60 void particles (CSS animation, no canvas)
- Formspree for contact form

## Design Rules

- **0px border-radius everywhere** — block geometry
- Chorus purple is the **one accent**; portal cyan for **one CTA only**
- Every section has a `// code-style` label
- Mobile-first, works at 375px
- No heavy libraries — loads fast on GitHub Pages

## Deployment

```
1. Create repo: ysdvision.github.io
2. Push index.html to root of main branch
3. Settings → Pages → Source: main / root
4. Live at https://ysdvision.github.io
```
