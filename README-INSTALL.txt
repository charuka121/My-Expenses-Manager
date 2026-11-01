ADVANCED EXPENSE MANAGER — INSTALLABLE PHONE APP (PWA)

This package is a Progressive Web App. It can be installed from a website onto Android
using Chrome, without Android Studio or an administrator password.

PUBLISHING (GitHub Pages):
1. Extract this ZIP on your computer.
2. Open your GitHub repository: My-Expense-Manager.
3. Upload ALL contents of this folder (index.html, manifest.webmanifest, sw.js,
   and the icons folder) into the repository root. Do not upload only the ZIP.
4. Commit the uploaded files.
5. In the repository, open Settings > Pages.
6. Under "Build and deployment", select "Deploy from a branch".
7. Select branch "main" and folder "/ (root)", then Save.
8. Wait for GitHub Pages to publish. The website URL will look like:
   https://charuka121.github.io/My-Expense-Manager/

INSTALL ON ANDROID:
1. Open the published website URL in Google Chrome on the phone.
2. Tap the three-dot menu.
3. Choose "Install app" (or "Add to Home screen", depending on Chrome).
4. Confirm Install / Add.
5. Open "Expense Manager" from the phone home screen. It opens like an app.

IMPORTANT:
- HTTPS hosting is required for installation/offline service worker support.
- The app stores records in the browser on that phone. It does not sync automatically
  to another phone/computer. Use Backup JSON regularly and keep the backup safe.
- Do not clear Chrome site data unless you have exported a backup.
