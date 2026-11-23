# The Anxious Click

Click track app with setlists, tempo maps and M-Vave Chocolate Plus pedal control.

## Put it online (GitHub Pages)
1. Create a new public repo named exactly `YOURUSERNAME.github.io`.
2. Upload every file and folder from this download (including the hidden `.nojekyll` file and the `.well-known` folder).
3. Repo Settings > Pages > Build and deployment > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`. Save.
4. After a minute, open `https://YOURUSERNAME.github.io` in Chrome on your phone. Tap the menu > Install app to check it works.

## Make the APK
1. Go to https://www.pwabuilder.com and enter `https://YOURUSERNAME.github.io`.
2. Choose Package for stores > Android. Keep the default options and generate.
3. Download the zip. It contains the APK, a signing key (keep it safe) and `assetlinks.json`.
4. Upload `assetlinks.json` into this repo at `.well-known/assetlinks.json` (replace the placeholder). This removes the browser address bar inside the app.
5. Copy the APK to your phone and install it (allow "install unknown apps" when asked).
