RICK RICH — ANDROID INSTALLABLE WEB APP

This package is a Progressive Web App (PWA), not a standalone APK. After HTTPS hosting, open it in Chrome on Android and choose ⋮ > Add to Home screen / Install app.

Upload these files to the ROOT of your GitHub repository:
- index.html (rename Rick_Rich_PWA_index.html to index.html before uploading)
- manifest.webmanifest
- service-worker.js
- icon.svg

Then enable GitHub Pages: repository Settings > Pages > Deploy from a branch > main > /(root).
Website address should be https://l3xus032.github.io/rick-rich/

Firebase:
- Enable Email/Password in Firebase Authentication.
- Add l3xus032.github.io in Firebase Authentication > Settings > Authorized domains.
- Keep database rules restricted to authenticated users; do not make the database public.

A native APK requires an additional Android build and signing process.
