# Optimus V.1 · Chiller Plant Designer

Online version of **Optimus V.1** (McEnergy) — chiller plant graphics in 2D / 3D, HMI screen and Grafana export.
Runs in the browser, no install. Plans are saved in the browser on each computer (localStorage).

## Put it online with GitHub Pages
1. Create a new repository on GitHub, e.g. `optimus`.
2. Upload **everything in this folder** to the repository root (keep the `icons` and `Graphics` folders and the `.nojekyll` file).
3. Repository → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**.
4. After about a minute the program is at `https://<your-user>.github.io/optimus/`.

## Install as an app (optional)
Open the link in Chrome or Edge → the install icon in the address bar (or menu → *Install Optimus*).
It then opens in its own window with the Optimus icon, and works offline after the first visit.

## Update
Replace `index.html` with the new version and commit. Users get it the next time they open the page.

## Files
| File | What it is |
|---|---|
| `index.html` | the program (three.js and fonts built in) |
| `Graphics/Optimus-Graphic-Converter.html` | 3D model converter (opened from the program) |
| `manifest.webmanifest`, `sw.js` | app install + offline support |
| `favicon.ico`, `icons/` | icons |
| `.nojekyll` | tells GitHub Pages to serve the files as they are |
