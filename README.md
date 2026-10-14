# TSPSC Mains Notes — Android app (PWA)

Minimal, offline notes + model answers + FSRS flashcards for TSPSC Group-1 Mains.

## Install on your Android phone (5 minutes)
1. Create a GitHub repo (e.g. `mains-notes`) and upload all files in this folder:
   `index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, icon-maskable-512.png`
2. Repo → Settings → Pages → Deploy from branch → `main` / root → Save.
3. Open `https://<username>.github.io/mains-notes/` in **Chrome on Android** → ⋮ → **Install app**.
   It now opens full-screen from the home screen and works offline.

## Want a real APK instead?
Go to https://www.pwabuilder.com, paste your GitHub Pages URL → Package for stores → Android → download.
The zip contains a signed `.apk` you can sideload (and the files needed for Play Store if you ever want it).
Note: the APK and the Chrome-installed version keep separate data — pick one and use backups to move.

## Workflow
1. **Add** → paste raw notes or Q&A → choose paper/options → **Copy prompt** (or *Share to app* to send straight to the ChatGPT/Claude/Gemini app).
2. Paste the AI reply back → **Check & preview** → **Save**. Notes, model answers and flashcards are created.
3. **Review** daily (FSRS scheduler, Again/Hard/Good/Easy). **Today** also lists notes due for re-reading (1-3-7-14-30-60-120 days).
4. **More → Answer practice** for timed answer writing with self-scoring.

## Data
Stored only on the phone (IndexedDB). Back up weekly: More → Backup & import → Download/Share.
Restoring offers Replace or Merge. Packs (.json) are shareable with friends and re-importable.
