# Latifah’s Birthday World

A private, bilingual birthday website made for Latifah by her big brother Mounir.

## Theme

Hello Kitty and Stitch, with pink bows, sky-blue accents, and original family photos. Character artwork sources are documented in `dist/assets/ATTRIBUTION.md`.

## Features

- English/French language switch
- 17 family photos with a gallery and full-size viewer
- Hello Kitty photo memory game, six-question character quiz, and Stitch star-catching game
- A short personal letter
- A candle-free cake, personal du’a, and confetti finale
- Optional synthesized music and reduced-motion support

## Run locally

No build or dependencies are required. With Python 3 installed, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000.

## Files

- `dist/index.html`: page shell
- `dist/style.css`: responsive styling
- `dist/app.js`: bilingual content and interactions
- `dist/assets/`: family photos

Deploy `dist/` as the static website directory on a host of your choice. The `gh-pages` branch contains a ready-to-publish copy at its root. GitHub Pages is not yet enabled because the current account requires a public repository or paid plan for this private project. The existing hosted website remains available.

## Privacy

Keep this repository private: it contains personal family photos. Only the selected language is stored in the visitor’s browser; game progress stays in memory. The app contains no analytics or keystroke tracking.
