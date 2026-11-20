# kids-learning

Website for **Phonics House**, a phonics reading game for children aged 3 to 7 (iPhone and iPad).

Live at https://barqawiz.github.io/kids-learning/ (GitHub Pages, deployed from `main`, root folder).

| Page | URL | Used for |
|---|---|---|
| Home | `/` | App Store marketing URL |
| Support | `/support.html` | App Store support URL, in-app help |
| Privacy Policy | `/privacy.html` | App Store privacy policy URL, linked from the paywall and settings |

Plain HTML and one stylesheet (`assets/site.css`), no build step. Images in `assets/` are the game's own art and
real screens from the iOS simulator. Push to `main` and Pages republishes in about a minute.

If the app's data collection, permissions or purchase options change, update `privacy.html` and `support.html`
in the same release.
