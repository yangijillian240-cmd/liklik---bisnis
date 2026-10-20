LIKLIK BISNIS MANAGER — OFFLINE PWA PACKAGE

Important:
- This package adds install/offline support to your existing HTML app.
- It must be published on a secure HTTPS website before Chrome can register the service worker and offer proper PWA installation.
- Opening index.html directly as a content:// file does NOT activate service-worker offline installation.
- Your business records are stored locally in the browser on this device. Use the app's Backup tab regularly and keep backup JSON files somewhere safe.
- Do not clear browser/site data unless you have a backup.

Files:
- index.html: your existing app with PWA setup added
- manifest.webmanifest: app name, icon and standalone display settings
- service-worker.js: caches the app shell for offline opening
- icon-192.png and icon-512.png: app icons

Next:
1. Upload all five files to the same folder on an HTTPS host (for example, a static site host).
2. Open the hosted HTTPS address in Chrome on your phone while online.
3. Wait for the page to finish loading, then open Chrome menu and choose Install app or Add to Home screen if offered.
4. Open the installed app once while online, then test Airplane mode.
5. Add a test product and export a backup before entering real business records.
