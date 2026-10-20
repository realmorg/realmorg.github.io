# realmorg.github.io

Serves the REALM website at https://realm.js.org/.

The site's source lives in [realmorg/realm](https://github.com/realmorg/realm) (`apps/site`). The `Website` workflow here checks it out, builds it and deploys it to GitHub Pages. Nothing built is committed. It runs when `realm`'s `main` branch changes (`realm` pushes an empty commit to the `rebuild` branch here, using a deploy key), every hour as a fallback, and on demand from the Actions tab.
