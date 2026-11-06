SNOW REMOVAL ROUTE TRACKER — ANDROID INSTALL PACKAGE

This is an installable web app (PWA), not a Play Store APK.
It must be hosted on an HTTPS website before Android/Chrome can install it.
The satellite map and map library load over the internet.

Files:
- index.html: tracker
- manifest.webmanifest: app name, icon and install settings
- sw.js: caches the app shell for repeat launches
- icon-192.png and icon-512.png: app icons

HOSTING AND INSTALLING:
1. Upload all files in this folder to an HTTPS static website (for example, a GitHub Pages site).
2. Open that website's address in Chrome on your Android phone.
3. Open Chrome's menu (three dots) and choose "Install app" or "Add to Home screen".
4. Confirm. The Snow Tracker icon will appear on your home screen.

DATA:
Customer list/statuses are stored in this browser's local storage. Use Export backup regularly.
Do not clear Chrome site data unless you have exported a backup.
