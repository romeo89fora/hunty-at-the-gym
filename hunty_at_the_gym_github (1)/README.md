# Hunty at the Gym — GitHub Pages

This repo contains a zero-dependency PWA that runs offline on iPhone/Android.
It uses only static files, so GitHub Pages can host it.

## 60‑Second Deploy (Project Pages)
1. Create a new repository on GitHub named **hunty-at-the-gym** (or any name).
2. Click **Add file → Upload files** and drag everything from this folder.
3. After upload, **Commit changes**.
4. Go to **Settings → Pages**.
5. **Source**: choose **Deploy from a branch**.
6. **Branch**: select **main** (or **master**) and **/ (root)** folder → **Save**.
7. Wait ~1–3 minutes. Your site appears at:

   `https://USERNAME.github.io/REPO-NAME/`

   Example: `https://romeo-silva.github.io/hunty-at-the-gym/`

## Add to Home Screen (iPhone)
1. Open the URL in **Safari**.
2. Tap **Share** → **Add to Home Screen**.
3. Launch from the icon. It works offline after first load.

## Notes
- All paths are relative (`./`), so it works under a subpath.
- `404.html` is included for SPA-style routing safety.
- Data is stored in `localStorage` on the device.