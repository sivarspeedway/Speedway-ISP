Speedline PWA

1. Create a public GitHub repository (e.g. speedline-app).
2. Upload all files in this folder to the repository root.
3. Settings > Pages > Deploy from a branch > main / (root) > Save.
4. Open https://YOUR-USERNAME.github.io/speedline-app/ in Safari or Chrome.
5. On iPhone: Safari > Share > Add to Home Screen. On Android: browser menu > Install app / Add to Home screen.
6. To change the destination URLs, edit links.json and commit. The PWA fetches this file fresh on each opening (when online).

Notes: GitHub Pages is public hosting. Do not put secrets in links.json. The two destination websites open in the browser. This is an installable website, not an App Store / Play Store native app. Users must be online to get updated URLs. The app falls back to the original URLs if the JSON cannot be fetched. The current icons are placeholders.
