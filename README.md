# BIAS

A swipe-force web app for magicians. Pick a poster in setup, let the spectator spin through famous movies, and the forced spin lands on yours. Every forced title spells a number on a calculator (B=13, I=1, A=4, S=5, O=0, Z=2, G=6), so BIAS is 13145.

## Install on iPhone
1. Open https://yairsarig-lgtm.github.io/BIAS/ in Safari.
2. Share, then Add to Home Screen.
3. Open it once while online; after that it works offline.

## Replacing the icon
Swap these files with your own artwork, same names and sizes:
- `apple-touch-icon.png` (180x180, iPhone home screen)
- `icon-192.png`, `icon-512.png` (Android and install prompts)
- `icon-maskable-512.png` (512x512, keep the artwork inside the middle 80%)
- `favicon-32.png` (browser tab)

After changing files, bump `CACHE` in `sw.js` (for example `bias-v2`) so installed copies pick up the update.
