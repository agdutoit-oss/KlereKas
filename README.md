# KlereKas

A personal wardrobe and 360º try-on app for iPhone. Upload photos of yourself from several angles, build your wardrobe from hats to shoes (paste a shop link, take a photo, or pick from your library), and try outfits on.

**Live:** https://agdutoit-oss.github.io/KlereKas/

## What works now

- **Guided photo shoot** (Home › Me card › Photo shoot): 8 full-length angles, one every 45º, and 5 head close-ups. A dashed outline shows how to stand for each angle, and a dial shows which angles are done. Hands-free mode counts down and reads each turn aloud, so the phone can sit on a tripod. Any angle can be retaken, or picked from the photo library.
- **360º view**: once all 8 full-length photos are taken, the Me card on Home spins through them. Drag to turn.
- **Saved on the phone**: photos, wardrobe pieces, the wishlist and looks are kept in the browser's on-device storage (IndexedDB).
- Reading a shop link is still a placeholder, and clothes are not yet drawn onto the photos (that needs an AI try-on service later).

## Privacy

This repository is public. Your photos are stored only on your iPhone, inside the app. They are never uploaded and must never be committed here. Deleting the app from the home screen deletes them too.

## Put it on your iPhone home screen

1. Open the live link in **Safari** on your iPhone.
2. Tap the **Share** button (square with an arrow).
3. Tap **Add to Home Screen**, then **Add**.

The KK crest appears on your home screen and the app opens full screen.

## Files

- `index.html` – the app
- `sw.js` – service worker, so the installed app updates and opens offline
- `manifest.json` – app name, colours and icons
- `apple-touch-icon.png`, `icons/` – home screen icons
