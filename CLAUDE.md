# body-clock-app

Goal: installable (Add to Home screen), offline copy of Body Clock for Boss's phone.

- Source of truth for the page: ~/pro-brief/builds/body-clock.html (brief: ~/pro-brief/briefs/body-clock.md). index.html here = that page + manifest link + service worker registration. Rebuild index.html after any change there.
- Files: index.html, manifest.webmanifest, sw.js (offline cache; bump the cache name C on each release), icon-192.png, icon-512.png.
- Hosting: LIVE since 2026-11-11 at https://templeply.github.io/body-clock/ (public repo templeply/body-clock, GitHub Pages from main, Boss approved). To update: rebuild index.html, bump C in sw.js, commit, ask Boss before pushing.
- Never put the prompt library or anything from ~/pro-brief/source in this folder.
