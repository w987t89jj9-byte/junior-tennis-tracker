JUNIOR TENNIS TRACKER V2 — INSTALLABLE OFFLINE WEB APP

FILES TO UPLOAD TO GITHUB PAGES:
  index.html
  mobile_tracker.html
  manifest.webmanifest
  sw.js
  icons/ (all PNG icons)

HOSTING VIA GITHUB PAGES (FREE)
1. Create/sign in to a GitHub account.
2. Create a new PUBLIC repository, e.g. junior-tennis-tracker.
3. Upload index.html, mobile_tracker.html, manifest.webmanifest, sw.js and the icons folder, keeping the folder structure.
   Tip: upload the files extracted from this ZIP, not the ZIP itself.
4. Repository Settings > Pages > Build and deployment > Deploy from a branch.
5. Select main and /(root), then Save.
6. Wait for GitHub to publish the site. It will be at:
   https://YOUR_USERNAME.github.io/junior-tennis-tracker/
7. Open that URL in Safari on the iPhone.
8. Safari Share > Add to Home Screen > Add.
9. While online, launch the new home-screen icon ONCE and let the app load completely.
10. Switch on Airplane Mode and reopen the icon to confirm offline operation BEFORE relying on it at a match.

NOTES
- GitHub Pages hosts only app code; match data stays in the browser's local storage.
- Data saved in Edge or from a local HTML file will NOT automatically transfer to the home-screen Safari app.
  Export JSON from your old tracker; then import it into the installed PWA.
- iOS can isolate storage between Safari and the home-screen app. Export and import JSON to migrate.
- Match records are NOT synced between devices.
- Back up match JSON after each match. Clearing site data, uninstalling the app, or iOS storage cleanup can remove local data.
- Don't use private/incognito browsing to track matches.
- This package preserves the V2 scoring and shot/error tracking behavior; it adds install/offline support.
- Offline support requires HTTPS hosting and a successful first online load. Opening index.html from Files does not install the PWA.
- The Python dashboard is included; run it on your Windows computer after exporting JSON.
- To update the app later, upload the updated files to the same repository. Export your data before updating.
- Public GitHub Pages means the app source is publicly accessible; your locally saved match data is not uploaded by the app.
