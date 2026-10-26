# Chorecraft

A gentle household quest game. Choose today's flame, get one small quest, begin in one tap, and watch the realm recover.

Live at `https://<your-github-username>.github.io/chore-quest/` once GitHub Pages is on.

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The whole game: markup, styles and script in one file |
| `a/` | Pixel avatars and icons (WebP) |
| `icons/` | App icons for the browser tab and home screen |
| `manifest.webmanifest` | Lets phones add Chorecraft to the home screen |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

No build step and no dependencies. Fonts load from Google Fonts.

## Turning on GitHub Pages

1. Push these files to the root of the `main` branch of `chore-quest`.
2. In the repo, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, then choose `main` and `/ (root)`. Save.
4. The site appears at `https://<your-github-username>.github.io/chore-quest/` within a minute or two.

## Saving

Progress saves in the browser you play in (`localStorage`). Each browser and device keeps its own copy, and clearing site data erases it.

To move progress, open **The Long Record → Move your save**, copy the save code, and paste it into Chorecraft wherever you open it next. This also brings progress over from the Claude version of Chorecraft.

## Adding it to your phone

- **iPhone:** open the site in Safari, tap Share, then *Add to Home Screen*.
- **Android:** open it in Chrome, tap the menu, then *Add to Home screen* (or *Install app*).
