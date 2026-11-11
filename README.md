# My Freedom Plan

A personal retirement and investment planner that installs on your phone and works offline.
Your numbers are saved only on your own device.

## Put it on GitHub Pages (free)

1. Sign in at github.com and create a new **public** repository, e.g. `freedom-plan`.
2. Click **Add file → Upload files** and upload everything in this folder
   (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder).
   Keep the `icons` folder as a folder. Click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to
   **Deploy from a branch**, Branch **main**, folder **/ (root)**, then **Save**.
4. Wait 1–2 minutes. Your app is live at
   `https://<your-username>.github.io/freedom-plan/`

## Install it on your phone

- **Android (Chrome):** open the link, tap ⋮ → **Install app** (or *Add to Home screen*).
- **iPhone (Safari):** open the link, tap Share → **Add to Home Screen**.

It opens full screen like a normal app and works without internet after the first visit.

## Updating later

Upload the new `index.html`, then change `freedom-plan-v1` to `freedom-plan-v2` in `sw.js`
so phones pick up the new version.

This is a learning tool, not investment advice.
