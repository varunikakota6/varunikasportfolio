# Portfolio

Static portfolio website for Varunika Kota.

## Deploy

This repository is configured to deploy to GitHub Pages automatically whenever you push to the `main` branch.

1. Create a GitHub repository named `portfolio` under your account.
2. Add it as a remote:
   ```bash
git remote add origin https://github.com/kotavarunika06/portfolio.git
   ```
3. Push to `main`:
   ```bash
git branch -M main
git push -u origin main
   ```
4. GitHub Actions will build and publish to the `gh-pages` branch.
5. Your site will be available at:
   `https://kotavarunika06.github.io/portfolio/`

## Resume live link

After deployment, update the live portfolio link in `resume.html` to your actual GitHub Pages URL.
