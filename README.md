# nabinatwgu.github.io

Personal site built from Nabin Pokhrel's resume/LinkedIn content. Single static file, no build step — GitHub Pages serves it as-is.

## Deploy

1. Create a new **public** repo on GitHub named exactly `nabinatwgu.github.io` (this exact name is what makes GitHub Pages serve it at the root domain instead of a project subpage).
2. From this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/nabinatwgu/nabinatwgu.github.io.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**. It should already show Source: `main` / `root` — if not, set it manually.
4. Visit `https://nabinatwgu.github.io` after a minute or two.

## Editing

Everything — content, styles, and the small year-stamp script — lives in `index.html`. Edit the text directly (About, Core Skills, Experience, Certifications, Contact sections are clearly marked), commit, and push. Changes go live within a minute or so of each push.

## Notes

- Uses Google Fonts (Space Grotesk, IBM Plex Sans, IBM Plex Mono) loaded via CDN — no local font files needed.
- Fully responsive; the two-column hero and stats grid collapse to a single column under 760px.
- Respects `prefers-reduced-motion` (disables the terminal cursor blink).
