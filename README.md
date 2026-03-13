# Youktik Sajjan — End Dimension Portfolio

Static GitHub Pages portfolio with a Minecraft End-inspired interface, an arcade-style dragon canvas background, and a separate blog page for essays, poetry, and literature.

## Files

- `index.html` — main portfolio page
- `blog.html` — separate writing page
- `cv.html` — embedded CV document
- `README.md` — project notes

## Current sections

- About
- Projects
- Ventures
- Culture
- Music
- Gallery (`Coming Soon`)
- Contact
- CV (final section)
- Blog / Poetry / Literature page in `blog.html`

## Visual system

- Void background: `#050508` / `#0a0b12`
- Surfaces: `#0f1020` / `#161830`
- Accent: chorus purple `#c084fc`
- CTA: portal cyan `#67e8f9`
- Fonts: Press Start 2P, VT323, Share Tech Mono, Nunito
- Geometry: `0px` border radius everywhere

## Interactive features

- Fixed canvas background with a 2D arcade-style Ender Dragon
- Dragon follows cursor movement and breathes fire
- Ambient Minecraft mobs spawn from screen edges
- GitHub project fetch for the selected public repo list
- Scroll-triggered reveal animations
- Separate blog page with category filters

## Publish to GitHub Pages

1. Create or use the repository `ysdvision.github.io`.
2. Upload these files to the repository root:
	- `index.html`
	- `blog.html`
	- `cv.html`
	- `README.md`
3. In GitHub repository settings, open `Pages`.
4. Set source to `Deploy from a branch`.
5. Choose branch `main` and folder `/ (root)`.
6. Wait for Pages to build, then open `https://ysdvision.github.io`.

## Notes

- The workspace is not currently a git repository, so no local `git add` / `git commit` / `git push` was possible here.
- The files themselves are ready to upload or commit from your GitHub repo folder.
