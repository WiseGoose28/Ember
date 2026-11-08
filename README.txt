EMBER V1.5 — VISUAL EXPERIENCE UPDATE
=====================================

This release refreshes EMBER's visual interface while preserving the existing
habit-tracking features and local data format.

Files in this release:
- index.html
- manifest.webmanifest
- sw.js
- ember-icon.svg (existing app icon; keep this file)

DEPLOY TO YOUR EXISTING GITHUB REPOSITORY
-----------------------------------------
1. Open the repository and make sure you have exported an EMBER backup first.
2. Replace index.html, manifest.webmanifest and sw.js in the repository root.
3. Keep ember-icon.svg in the repository root. Do not replace it.
4. You may replace README.txt with this updated copy.
5. Commit the changes and wait for GitHub Pages to finish deploying.
6. Open the website in Chrome, allow it to load the new version, then reopen
   the installed EMBER app.

DATA SAFETY
-----------
- The localStorage key remains ember_growth_v1.
- No data migration is performed.
- Goals, check-ins, archive/restore, delete, Insights, Time Machine, and
  import/export behaviour are retained.
- The service-worker cache version is updated so the new interface can load.
- GitHub commits do not back up the data stored on your device.

If anything looks wrong, do not clear Chrome site data or uninstall the app.
Export a backup before attempting any reset or recovery step.
