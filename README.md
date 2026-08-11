# SheComputes GitHub Pages site (scaffold)

This folder contains a simple static site scaffold for the SheComputes organization GitHub Pages.

How to publish as an organization Pages site:

1. In your GitHub account, create a new repository named `shecomputes.github.io` inside the `SheComputes` organization (you already created this).
2. From this folder, initialize git, commit, and push to the repo you created (example commands below):

```bash
# change into the folder where you cloned or placed this site
cd path/to/SheComputes.github.io
git init
git add .
git commit -m "Initial SheComputes.github.io site"
git branch -M main
git remote add origin git@github.com:SheComputes/shecomputes.github.io.git
git push -u origin main
```

3. GitHub automatically serves the pages site for an organization repository named `shecomputes.github.io` from the `main` branch — the site will be available at:

   https://SheComputes.github.io

Notes:
- This scaffold intentionally does not include or link to external-hosted images or third-party site content. If you want to add images, place them in an `assets/` directory and update `index.html` to reference them locally.
- If you want me to push these files to the repository for you, I can do so provided this machine has an authenticated `gh` or SSH access for your account.
