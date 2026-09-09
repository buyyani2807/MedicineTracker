# GentleDose

An accessible, privacy-first medicine reminder that can be hosted as a static GitHub Pages site.

## Privacy model

The site contains no backend, accounts, analytics, or shared database. Medicine schedules and taken history are saved in the browser's `localStorage` on each device. If two family members open the same GitHub Pages URL, they still see separate data unless they deliberately use the same browser profile and device. Do not use private/incognito mode if you want data to persist.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the files in this folder (`index.html`, `styles.css`, `app.js`, `manifest.json`, `sw.js`, and `app-icon.png`).
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Open the generated HTTPS URL. On a phone/tablet, use **Add to Home Screen** for the app-like experience and offline cache.

The browser's notification rules vary by device. The app remains useful with the page installed/open; truly reliable closed-app reminders require a native app or a push-notification service.
