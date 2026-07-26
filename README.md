# Woodpecker Trainer — PWA setup (one time, ~10 minutes)

This folder is your personal Woodpecker Method trainer, packaged as an
installable web app. The puzzle data (`data.enc`) is encrypted, so even on a
public host nobody but you can read the book content.

## Host it free on GitHub Pages

1. Go to github.com and sign in (create a free account if needed).
2. Click **+ → New repository**. Name it e.g. `woodpecker`, leave it Public, click **Create repository**.
3. On the new repo page, click the **"uploading an existing file"** link and upload ALL files in this folder
   (index.html, data.enc, sw.js, manifest.webmanifest, icon-192.png, icon-512.png). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
5. After a minute your app is live at:  `https://YOUR-USERNAME.github.io/woodpecker/`
6. Open that link, enter your passphrase (Claude sent it to you in the chat), and you're in.
7. In Chrome, open the ⋮ menu and tap **Add to Home screen** (or "Install app").
   It now behaves like a native app: home-screen icon, full screen, works offline.

## Notes

- Your progress is saved in the browser at that address — stable and reliable,
  unlike opening a downloaded file. Still, an occasional **Export progress**
  backup (in Settings) is wise; **Import** restores it anywhere.
- If you had progress in the single-file version, export it there and import it here.
- The app works fully offline after the first visit.
- To update the app later, just replace the files in the repo.
- Keep this for your personal use only — the puzzles are from your copy of
  The Woodpecker Method (Smith & Tikkanen, Quality Chess).
