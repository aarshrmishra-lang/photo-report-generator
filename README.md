# Photo Reports: installable app

Upload all the files in this folder to a GitHub Pages site, like your Marine Cards app.

1. On github.com, create a new repository named `photo-reports`.
2. Open it, choose **Add file › Upload files**, drag in every file from this folder (index.html, sw.js, manifest.webmanifest, the icon PNGs), then **Commit changes**.
3. Go to **Settings › Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and the folder to **/ (root)**, then **Save**.
4. After a minute the app is live at `https://<your-username>.github.io/photo-reports/`.

## Install on each device
- **Android (Chrome):** open the link and tap **Install app** (or menu › Install app).
- **iPhone/iPad (Safari):** open the link, tap **Share › Add to Home Screen**.
- **Windows/Mac (Chrome or Edge):** open the link and click the install icon in the address bar.

After the first open, the app works offline. Reports and photos stay on each device.

## Updating
To update the app later, upload the new index.html (and sw.js) to the same repository. Devices pick up the new version the next time they open the app while online.
