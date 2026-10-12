# TimeZone Meeting Planner — installable PWA

This package turns the responsive meeting planner into a Progressive Web App (PWA) for Android/Samsung phones.

## Install on Samsung
1. Upload the contents of this folder to a static web host that serves HTTPS (for example GitHub Pages or Netlify).
2. Open the hosted `index.html` URL in Chrome on your Samsung phone.
3. In Chrome, tap ⋮ and choose **Install app** or **Add to Home screen**.
4. Confirm. It will appear as an app icon and open in its own window.

A local HTML file opened directly from Downloads cannot be fully installed as a PWA; HTTPS hosting is required for the service worker/offline behavior.

## Files
- `index.html` — the app
- `manifest.webmanifest` — install metadata
- `service-worker.js` — offline cache
- `icons/` — app icons

The app does not require an account or server-side database. Meeting data is generated locally in your browser.
