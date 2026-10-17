# The Day of Poo — iPhone Edition V13

A self-contained sketchbook-style game based on V12, with PWA installation, iPhone Safari adjustments, tilt and touch controls, and offline caching.

## Easiest installation using GitHub Pages

1. Unzip this folder.
2. Create a new public GitHub repository, for example `day-of-poo`.
3. Upload ALL files from the `the_day_of_poo_iphone_v13` folder into the repository ROOT. **Do not upload just `index.html`.**
4. In repository **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)` and Save.
5. Once deployment finishes, open the resulting HTTPS site address on your iPhone in **Safari**.
6. Tap the Safari **Share** button → **Add to Home Screen** → enable **Open as Web App**, if offered → **Add**.
7. Open the Home Screen icon while online once; afterwards it can load offline.

## Controls

- Drag across the game to move left or right; your finger does not need to sit on the character.
- Tap the green pause button in the upper left.
- Optional: press **Enable phone tilt** on the start screen; iOS will ask for motion access. If permission is denied or unavailable, touch works normally.
- Keyboard: left/right or A/D, P to pause, M mute, C changes unlocked city.

## Notes

- Home Screen installation/offline caching needs an HTTPS host, not a local `file://` path. GitHub Pages is free for public repositories.
- Some Safari versions show **Add to Home Screen** under the share sheet or the browser menu.
- The game runs in portrait; iOS may not forcibly lock orientation when opened in a normal Safari tab.
- Browser scores are stored locally and may not transfer between addresses or Safari/private browsing and Home Screen app storage.
- An update to the game after installation may require reopening online to download the updated cache.
