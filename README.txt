NSC Manager 2.0 — Installable PWA

FILES:
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

DEPLOY:
1. Upload ALL files/folders keeping this exact structure.
2. On GitHub Pages: put them in the repository root (or the selected Pages folder).
3. On Netlify: deploy the NSC_PWA folder.
4. Open the HTTPS site in Chrome on Android.
5. Chrome should offer Install app / Add to Home screen when PWA criteria are met.

IMPORTANT:
- Keep manifest.json, service-worker.js and the icons folder in the same relative structure.
- The app data itself is stored locally in the browser. Use the built-in Export Full Backup regularly.
- WhatsApp reminders open a pre-filled WhatsApp message; fully automatic sending requires an official WhatsApp Business API/backend.
