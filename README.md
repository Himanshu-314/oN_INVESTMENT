# Investment Plan

Portfolio calculator, editor and suggestor (matches the Investment_Portfolio_Dashboard sheet). Works offline and installs on your phone.

## Put it on GitHub (free hosting)
1. Create a new public repository, for example `investment-plan`.
2. Upload every file in this folder (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png).
3. Repository Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/investment-plan/`.

## Install on your phone
- Android (Chrome): open the link, tap the three-dot menu, then "Install app" or "Add to Home screen".
- iPhone (Safari): open the link, tap Share, then "Add to Home Screen".

## Changing the defaults
Open `index.html` and edit the `DEF` block near the top of the script, or just change values inside the app
(they are saved on the device). To publish new defaults after editing, bump `CACHE` in `sw.js`
(for example `investplan-v2`) so phones pick up the update.
