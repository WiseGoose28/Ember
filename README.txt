EMBER V1.5 — BRAND IDENTITY UPDATE
==================================

This update applies the newly designed glowing-coal / cracked-ember mark throughout EMBER.

Replace these files in the ROOT of your existing GitHub repository:
- index.html
- sw.js
- manifest.webmanifest
- icon.svg (optional: safe to delete from the repository; the new app uses PNG icons)
Upload these NEW files to the same root:
- ember-mark.png
- icon-192.png
- icon-512.png

Important:
- Do not change the localStorage key. It remains ember_growth_v1.
- This is a visual/branding update; goals, check-ins, archives, Time Machine and backup data are unchanged.
- Existing installed PWA icons may take time to refresh. Chrome can cache home-screen icons; if the old icon remains, first allow the new site update, then remove and re-add the home-screen shortcut only after confirming your data is backed up. Removing a shortcut does not itself erase website localStorage, but avoid clearing site data.
- The original V1.4.1 files should be retained in GitHub commit history for rollback.

Deploy:
1. Export your EMBER data as a precaution.
2. Replace index.html, sw.js and manifest.webmanifest.
3. Upload ember-mark.png, icon-192.png and icon-512.png to the repository root.
4. Commit the changes and wait for GitHub Pages to deploy.
5. Open the site once in Chrome, then reopen the installed app.

