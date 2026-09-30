# Dr. D Burman PWA — Fixed Install Button

Upload these files to the root of the GitHub Pages repository:

- index.html
- manifest.webmanifest
- service-worker.js
- favicon.png
- icons/icon-192.png
- icons/icon-512.png

After uploading:
1. Wait for GitHub Pages to redeploy.
2. Open the HTTPS GitHub Pages URL in Google Chrome on Android.
3. Refresh the page.
4. Tap **📲 Install App**.
5. If Chrome has not exposed the install prompt yet, use **⋮ → Add to Home screen / Install app**.

The install button now:
- registers the service worker;
- listens for the browser's install event;
- shows a clear fallback message if the prompt is unavailable;
- changes to **✅ App Installed** after installation.
