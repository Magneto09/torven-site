# Torven Ventures – one-page site
Static site (no build step). Files: index.html, vercel.json, robots.txt.

## Deploy
Option A (drag & drop / CLI):
  npm i -g vercel
  cd torven-site
  vercel --prod

Option B (Git): push this folder to GitHub, then Vercel > Add New Project > Import.
Framework preset: "Other". Build command: none. Output directory: leave blank (root).

## Custom domain
Vercel project > Settings > Domains > add your domain and set the DNS records shown.
