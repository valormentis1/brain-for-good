# How to Manipulate Your Brain for Good

A responsive, installable Progressive Web App for learning about procrastination and practising behaviour change.

## Run locally

A service worker requires HTTPS or localhost. Do not open `index.html` as a `file://` URL if you want PWA installation/offline support.

With Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Alternatively, deploy the folder to any static HTTPS host.

## Included

- Six chapters with 18 short lessons
- Lesson completion tracking
- Post-learning personal reflection assessment
- Task decomposer and IF–THEN planner
- Five-minute timer
- Environment checklist
- Quick Rescue flow
- Flexible 14-day practice tracker
- Evidence library with source links
- Dark/light themes
- Local IndexedDB storage
- JSON export/import and delete controls
- Service worker cache and web app manifest

## Privacy

The application does not send tasks, assessment answers, reflections or progress to an application backend. Local data is stored in the browser's IndexedDB. Browser storage can be cleared by the user or browser; export backups regularly.

The Google Fonts import is an optional external font request when online. The system falls back to local system fonts when offline. Remove the `@import` line in `styles.css` for a fully self-contained no-third-party-network version.

## Research note

The included bibliography is a starter collection, not an exhaustive systematic review. Verify publication metadata and read source papers before relying on individual claims in a formal educational or clinical setting. This app is educational and not a diagnostic or treatment tool.

## Accessibility and compatibility

The interface is responsive and supports reduced-motion preferences and keyboard focus styles. Conduct device/browser and assistive-technology testing before public release. PWA installation behaviour differs by browser and operating system.
