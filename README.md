# Adept Style — Website

Redesigned single-page site for Adept Style Unisex Salon (Dartford & Plumstead).
The whole site is one self-contained `index.html` — no build step, no dependencies.

## Deploy to Vercel

**Option A — drag & drop**
1. Go to https://vercel.com/new
2. Drag this folder in. Vercel detects it as a static site. Click **Deploy**.

**Option B — from GitHub (recommended)**
1. Create a new GitHub repo and push this folder (see below).
2. In Vercel: **Add New… → Project → Import** your repo.
3. Framework Preset: **Other**. Build Command: leave empty. Output Directory: `./`.
4. Click **Deploy**.

**Option C — Vercel CLI**
```bash
npm i -g vercel
vercel        # preview
vercel --prod # production
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Adept Style site"
git branch -M main
git remote add origin https://github.com/<you>/adept-style-site.git
git push -u origin main
```

## Editing

All content (services, team, branches, reviews) lives inline in `index.html`.
Search for the text you want to change and edit it directly. Images are loaded
from remote URLs, so an internet connection is needed to see them.

---
© Adept Style Salon
