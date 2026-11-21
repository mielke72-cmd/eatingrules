# Fuel Plan

Personal eating, fuelling and hydration plan for the cut + Burj2Burj half-marathon block (race 24 Jan 2027).

Installable PWA, works offline. No build step, no dependencies.

## Deploy on GitHub Pages

1. Create a new repo (e.g. `fuel-plan`) and upload all files in this folder to the root.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. Open `https://<your-username>.github.io/fuel-plan/` on your phone.
4. iPhone: Share → *Add to Home Screen*. Android: menu → *Install app*.

## Updating

Edit `index.html` (plan text and the `DAYS` object at the bottom), commit, and bump `CACHE` in `sw.js`
(e.g. `fuel-plan-v2`) so phones pick up the new version.
