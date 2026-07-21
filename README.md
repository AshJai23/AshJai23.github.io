# Ashlin Jayakumar — Portfolio

Personal portfolio site for Ashlin Jayakumar, Data Scientist & ML Engineer.
Static HTML/CSS/JS — no build step, deploys straight to GitHub Pages.

**Live site:** `https://AshJai23.github.io` (once Pages is enabled — see below)

## Structure

```
index.html            main page (about, experience, projects, skills, education, contact)
assets/css/style.css  styles ("Signal" dark console theme)
assets/js/main.js     mobile nav + footer year
assets/Ashlin_Jayakumar_CV.pdf   downloadable résumé (linked from the hero button)
```

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploy to GitHub Pages

1. Create a new **public** repo on GitHub named exactly `AshJai23.github.io`
   (that exact name turns on a user site at the root domain).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/AshJai23/AshJai23.github.io.git
   git push -u origin main
   ```
3. In the repo → **Settings → Pages** → Source: `Deploy from a branch` →
   Branch: `main` / `root`. Save.
4. Site goes live at `https://AshJai23.github.io` within a minute or two.

## Editing

- Swap in real project repo links: replace the `https://github.com/AshJai23`
  placeholders in the project cards (`index.html`) with each project's actual
  repo URL once pushed.
- Update `assets/Ashlin_Jayakumar_CV.pdf` any time the résumé changes — the
  filename is what's linked from the "Download résumé" button.
