# My App Vault

Static storefront for direct APK distribution.

## Local preview
    python3 -m http.server 8000
Then open http://localhost:8000

## Deploy (GitHub Pages)
1. Push this folder to a GitHub repo.
2. Settings → Pages → Source: `main` branch, `/ (root)`.
3. Page goes live at `https://<username>.github.io/<repo>/`

## Adding an app
1. Upload the signed APK to a GitHub Release.
2. Add a card in `index.html`, linking to:
   `https://github.com/<user>/<repo>/releases/latest/download/<file>.apk`
