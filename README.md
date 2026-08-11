# SheComputes GitHub Pages site (scaffold)

This folder contains a simple static site scaffold for the SheComputes organization GitHub Pages.

How to publish as an organization Pages site:

1. In your GitHub account, create a new repository named `SheComputes.github.io` inside the `SheComputes` organization.
2. From this folder, initialize git, commit, and push to the repo you created (example commands below):

```bash
cd /scratch/cii2002/SheComputes.github.io
git init
git add .
git commit -m "Initial SheComputes.github.io site"
git branch -M main
git remote add origin git@github.com:SheComputes/SheComputes.github.io.git
git push -u origin main
```

3. GitHub automatically serves `main` branch for a repository named `ORG.github.io` — the site will be available at:

   https://SheComputes.github.io

Notes:
- This scaffold links images and flyers directly from the Hoffmann Group site to preserve attribution. If you prefer to host assets locally, download them into `assets/` and update the `index.html` image paths.
- If you want me to open a PR, push changes, or create the repo for you, I can help but will need access (or you can grant a temporary personal access token).
