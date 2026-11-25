Jayant at re:Invent 2026 - offline app (PWA) for Vercel or Netlify

DEPLOY
1. Unzip this folder.
2. Upload the WHOLE folder (index.html, sw.js, manifest.webmanifest, icons/) to your Vercel project
   (or drag it onto app.netlify.com/drop). Do not upload index.html on its own:
   sw.js is what makes the app open with no signal.
3. Keep the link private: it contains contact names and photos.

ON JAYANT'S PHONE (Android, Chrome)
1. Open the link once while online.
2. Chrome menu > Install app (or Add to Home screen).
3. From then on it opens from the home screen, even in airplane mode.

UPDATING
Replace index.html, change VERSION in sw.js (reinvent-v3 -> reinvent-v4), redeploy.
Jayant closes and reopens the app twice to pick up the new version.

DATA
Everything Jayant marks, people he adds and card photos are stored on his phone.
Each night: Report tab > Share report, Share CSV file, Share card photos to WhatsApp.
