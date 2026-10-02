# NOVA PWA

NOVA is now packaged as an installable Progressive Web App.

## Deploy
Upload these files to the same Vercel/GitHub project root:

- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

Do not change `api/chat.js`.

## Android installation
1. Open the deployed NOVA website in Chrome.
2. Wait for the page to finish loading.
3. Open Chrome's ⋮ menu.
4. Choose **Add to Home screen** or **Install app**.
5. Confirm.

The PWA keeps the NOVA interface available as a standalone app. Chat and satellite data still need an internet connection when they depend on the Groq/CelesTrak services.
