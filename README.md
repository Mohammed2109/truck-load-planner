# Truck Load Planner

Web tool that shows a 3D truck and fills it with bins as you add them.
Set the truck size (default 53 ft × 8 ft 6 in × 13 ft 6 in), add bins of different
sizes (inches, feet, cm or m), set the loading order, and replay the load bin by bin.

Pure static site (HTML + JavaScript, three.js loaded from cdnjs) — no build step.

## Run locally
Open the folder in VS Code, right-click `index.html` → **Open with Live Server**.

## Deploy
Hosted on **Azure Static Web Apps** (Free plan). Every push to `main` redeploys
automatically through the GitHub Actions workflow that Azure adds to `.github/workflows/`.

Azure build settings: App location `/`, API location *(empty)*, Output location *(empty)*.

## Files
- `index.html` – the whole app
- `staticwebapp.config.json` – Azure Static Web Apps routing
