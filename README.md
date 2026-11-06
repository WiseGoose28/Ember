# EMBER v1.0 — Personal Growth PWA

## What is included
- Nickname and goal onboarding; each goal has an emoji.
- Day 1 begins on the date you commit during onboarding.
- One-tap daily completion check-ins, stored locally on your device.
- Analytics: completion rate, perfect-day streak, best day, daily trend and per-goal consistency.
- Calendar view, goal editing, JSON backup export, offline service worker.
- Dark-only interface with warm orange accent; optional Android vibration feedback.

## Install on Android
This is a Progressive Web App (PWA). To install it, it must be served from an HTTPS website (or localhost).
1. Upload the contents of this folder to a static host such as GitHub Pages, Cloudflare Pages or Netlify.
2. Open the resulting HTTPS URL in Chrome on Android.
3. Open Chrome's menu (⋮) and choose **Install app** or **Add to Home screen**.
4. Launch EMBER from your home screen.

Opening index.html directly from a file manager is useful for a quick preview, but browser storage and PWA installation may not work reliably from file:// URLs.

## Data and privacy
Your profile, goals and check-ins are saved in localStorage on that browser/device. They are not synced to an account or cloud. Use **Goals → Export my data** to download a JSON backup. Clearing browser site data will remove the app's local data.

## V1 limitations
- Data is local to one browser/device; no account or cross-device sync.
- Haptics are best-effort via the browser's Vibration API and may be unavailable on some devices.
- Calendar currently displays the current month; charts summarize the last 14 days.
