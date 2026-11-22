MY MONEY MONTH — INSTALLABLE PWA PACKAGE

Files:
- index.html: the expense tracker app
- manifest.json: app identity and install settings
- service-worker.js: offline cache
- icon.svg / icon-192.png / icon-512.png: app icons

IMPORTANT:
A PWA must be served from HTTPS (or localhost) to install and use service-worker/offline features. Opening index.html directly as a file will not enable installation.

EASIEST HOSTING OPTION — GitHub Pages:
1. Sign in/create a GitHub account.
2. Create a new repository named my-money-month (Public is simplest for free Pages hosting).
3. Upload all files in this folder to the repository root.
4. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), Save.
5. Wait for GitHub Pages to publish. Open the provided HTTPS website URL in your phone browser.
6. iPhone: Safari > Share > Add to Home Screen.
   Android: Chrome > menu (three dots) > Install app / Add to Home screen.

DATA:
Your current app stores budget and expense records in browser local storage on that device. This package does not sync data between devices. Export CSV regularly as backup. Clearing browser/site data can erase records.
