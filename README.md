# Game Center

A small set of browser games that also run in a VR headset (built for Meta Quest 2).

Play: https://thegoose12.github.io/breadrun/

- `index.html` is the game picker.
- `bread/index.html` is Bread Run, a voxel city game. One file, no build step, three.js from a CDN.
- New games go in their own folder (for example `everest/index.html`) and get a card in `index.html`.

Publishing: push to `main`, then push `main` to `gh-pages`. GitHub Pages serves `gh-pages`.
