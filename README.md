# realmui.github.io

Serves the REALM website at https://realmui.github.io/.

The site's source lives in [realmui/realm](https://github.com/realmui/realm) (`apps/site`). The `Website` workflow here checks it out, builds it and deploys it to GitHub Pages. Nothing built is committed. It runs when `realm`'s `main` branch changes, every hour as a fallback, and on demand from the Actions tab.
