# Leva H3LL — Social Hub

A minimal dark personal social hub with animated link cards and a downloadable QR code.

## Run locally
Open `index.html` in a browser. An internet connection is needed for Google Fonts and the QR-code library CDN.

## Customize
Edit `config.js` to change or add social links. Each item uses:
```js
{ name: "Platform", handle: "@username", url: "https://example.com" }
```

## Publish with GitHub Pages
1. Create a GitHub repository, for example `social-hub`.
2. Upload `index.html`, `config.js`, and this README to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. After GitHub Pages publishes the site, open its public URL.

The QR code is generated from the page's current URL. Once the site is deployed, it points to the published page. Keep the repository/site URL unchanged if you want the printed QR code to remain valid.
