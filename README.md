# MOOLAAAAAAH!! app

Stand-alone, installable version of the MOOLAAAAAAH!! expense tracker.

- Static site: `index.html`, `manifest.webmanifest`, `sw.js`, `icons/`. Hosted on GitHub Pages.
- Data: Firebase Firestore, stored under `users/<your uid>/` (`months`, `loans`, `settings`). Sign-in is with Google.
- `config.js` holds the Firebase web config (identifies the project; not a secret).
- `firestore.rules` limits every account to its own data. Paste it into Firestore → Rules.
- Works offline after the first load. Changes sync when the phone is back online.

Your data backup is never stored in this repository.
