# Apex Asset Management — Website

Single-page marketing website for Apex Asset Management International.

## Structure

```
/
└── index.html   ← entire site (self-contained, no dependencies)
```

## Deployment via IONOS

This site is deployed as a **static site** via GitHub + IONOS Deploy Now.

### First-time setup

1. Push this repo to GitHub (see below)
2. Log in to [IONOS](https://www.ionos.co.uk) → **Deploy Now**
3. Connect your GitHub account and select this repository
4. Set build type to **Static** (no build step needed)
5. Set publish directory to `/` (root)
6. Deploy — IONOS will auto-deploy on every push to `main`

### Pushing to GitHub

```bash
# 1. Initialise the repo (first time only)
git init
git add .
git commit -m "Initial commit"

# 2. Add your GitHub remote (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/apex-website.git

# 3. Push
git branch -M main
git push -u origin main
```

### Updating the site

```bash
git add .
git commit -m "Update site"
git push
```

IONOS will detect the push and redeploy automatically.

## Contact

All enquiries → info@apexglobalasset.com
