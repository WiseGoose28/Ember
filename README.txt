EMBER V1.4 UPDATE
=================

Replace these two files in the ROOT of your existing GitHub repository:
- index.html
- sw.js

Do not replace manifest.webmanifest or icon.svg; they are unchanged.

What's included:
- Today page: checklist first; separate Journey and Today's Progress cards below.
- Consistent white, bold page headings: Today's Checklist, Insights, Your System.
- Insights: title above Goal Specific / Overall tabs; Longest Streak added.
- Goal management: Archive, Restore, and permanent Delete with confirmation.
- Archived goals preserve their history; they stop appearing in active tracking.
  Their check-ins remain counted in the Overall chart only for dates up to the archive date.
- Import Backup with validation and explicit replace confirmation.
- Export now includes a small format/version wrapper; importer also accepts older raw JSON exports.
- Time Machine remains available and can edit historical dates for goals that existed then.

DATA SAFETY:
- The app keeps the existing localStorage key: ember_growth_v1.
- The existing data structure is preserved; archivedAt is added only to archived goals.
- Before importing, export your current data. Import replaces the current database.
- Permanent deletion removes that goal's check-ins from all dates. It cannot be undone except from a backup.

Deploy:
1. Upload/replace index.html and sw.js in the repository root.
2. Commit both files.
3. Wait for GitHub Pages deployment.
4. Open the site in Chrome and allow the new service worker to update.
