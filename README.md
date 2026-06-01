# Dashboard E‑Commerce (Static Web Version)

This folder contains a **stand‑alone, static** version of the Electron dashboard that can be served as a regular website (e.g., via GitHub Pages).

## Contents
- `index.html` – The full HTML page with all CSS/JS inline and external CDN references (Google Fonts, SheetJS, Chart.js, Lucide).  
- `assets/` – Folder with the application icon (you can add more assets here if needed).

## How to Deploy
1. Open a terminal in this folder.
2. Initialise a Git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial static site commit"
   ```
3. Create a remote repository on GitHub (or any other Git host).
4. Push the code:
   ```bash
   git remote add origin <YOUR_REPO_URL>
   git branch -M main   # or gh-pages if you prefer that branch
   git push -u origin main
   ```
5. Enable **GitHub Pages** in the repository settings. Choose the `main` (or `gh-pages`) branch as the source.

The site will be available at `https://<username>.github.io/<repo>/`.

---
*All assets are loaded from CDN, so the site works without any server‑side code.*
