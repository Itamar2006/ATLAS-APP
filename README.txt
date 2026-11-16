# ATLAS — PWA starter

This is the first installable-web-app package for the ATLAS prototype.

## What is included
- `index.html` — the current dark bilingual prototype.
- `manifest.webmanifest` — tells compatible browsers that this is an installable app.
- `sw.js` — caches the app shell for basic offline opening after the first visit.
- `icon.svg` — app icon.

## Important limitations
- This is not yet an AI agent. No AI model/API is connected.
- Course data is currently stored in the browser's localStorage on one device.
- Offline support caches the interface; it does not add cloud sync or AI.
- Installability generally requires hosting over HTTPS (or localhost).

## Next step
Publish this folder to a static HTTPS host (for example GitHub Pages), open the resulting URL in Chrome on Android, then use Chrome's menu > Install app / Add to Home screen.

Do not upload private learner data to a public repository. This starter contains no personal data.
