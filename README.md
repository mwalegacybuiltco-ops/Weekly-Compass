# April’s Weekly Compass

## Put this PWA on GitHub Pages
1. Download and unzip this file.
2. Create a GitHub repository.
3. Upload all the extracted files into the repository root. index.html must be at the top level, not inside a folder. Upload the files, not this ZIP.
4. Open repository Settings → Pages.
5. Under Build and deployment choose Deploy from a branch, select main and / (root), then Save.
6. Open the Pages link GitHub provides after deployment finishes.

On iPhone: open that link in Safari → Share → Add to Home Screen.
Open online once to cache the app for offline use. HTTPS is required for the service worker.

## Data and privacy
Records save in the browser on each device. There is no automatic cross-device sync. Use Backup & help to download or restore a backup. Existing records from the ChatGPT-hosted version do not automatically move: download a backup there and restore it in your GitHub Pages app.
GitHub Pages does not include the private access protection of the ChatGPT-hosted site. Anyone with the Pages URL may open the empty app, but your entered records remain in your browser and are not uploaded to GitHub. Use a trusted device and keep backups.

## Files
index.html: interface
app.js: tracker and local saving
sw.js: offline cache
manifest.json: PWA settings
icon.svg: app icon
.nojekyll: enables plain static hosting

For future updates, change the CACHE version in sw.js so installed copies refresh their cached files.
