# Client Relationship Tracker

Live, multi-device client tracker. Static site on GitHub Pages, data in Firebase Firestore.

## Setup (once)

1. Create a Firebase project at https://console.firebase.google.com
2. Build -> Firestore Database -> Create database (production mode)
3. Rules tab -> paste the contents of `firestore.rules` -> Publish
4. Project settings -> Your apps -> Web app -> copy the config into `firebase-config.js`
5. Push to GitHub, then Settings -> Pages -> Deploy from branch `main` / root
6. Open the Pages URL, click **Import CSV**, choose `clients-seed.csv`

Anyone with the link can view and edit. Export CSV any time to get an Excel-compatible file.
