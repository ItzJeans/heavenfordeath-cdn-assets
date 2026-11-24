# Heaven for Death — Web Port

A browser-based port of **Heaven for Death**, a *Bocchi the Rock!* fan game. This project makes the game playable from a web browser without requiring players to install the original game locally.

## Play Online

**Play Heaven for Death:** [Daniel's Games](https://sites.google.com/view/danielsgxmes/games)

Find **Heaven for Death** in the games section.

## How It Works

The web port uses a single HTML launcher together with the original game engine and assets. The launcher loads the game's files from an npm package delivered through [jsDelivr](https://www.jsdelivr.com/).

- **Game launcher:** HTML, CSS, and JavaScript.
- **Asset hosting:** npm package `heavenfordeath-assets-itzjeans`.
- **Content delivery:** jsDelivr CDN.
- **Internet connection:** Required while playing, because the game loads its assets from the CDN.

The asset package is currently pinned to **version `1.0.1`** so the web port uses a consistent set of game files.

## Features

- Play the fan game in a modern desktop web browser.
- Game assets are delivered through jsDelivr.
- No separate game installation is required for players.
- Keyboard-based play; the on-screen touchscreen controls are not included in this build.

## Requirements

- A modern web browser (Chrome, Edge, Firefox, or another Chromium-/Firefox-based browser).
- An active internet connection.
- Access to `cdn.jsdelivr.net` so the game can download its assets.

## Credits and Disclaimer

**Heaven for Death** is a fan game based on *Bocchi the Rock!*. This browser port is an unofficial fan project and is not affiliated with, endorsed by, or sponsored by the original game's creators, the *Bocchi the Rock!* creators, or their publishers.

All original game content—including characters, artwork, music, story, and other assets—belongs to its respective creators and rights holders. This web port and its hosting setup do not claim ownership of that content. Please support the original creators and follow any permissions or conditions that apply to the original game and its assets.

## Troubleshooting

- **The game does not load:** Make sure your internet connection is working and that your network allows access to `cdn.jsdelivr.net`.
- **A resource-loading error appears:** The browser may be unable to retrieve an asset from the CDN. Try refreshing the page. If the problem continues, the hosted asset package or its CDN cache may need attention.
- **The game looks stuck while starting:** Give the initial assets a moment to load, then refresh the page if it does not continue.

## Project Information

- **Project:** Heaven for Death — Web Port
- **Asset package:** [`heavenfordeath-assets-itzjeans`](https://www.npmjs.com/package/heavenfordeath-assets-itzjeans)
- **Asset version used:** `1.0.1`
- **CDN:** [jsDelivr](https://www.jsdelivr.com/)
- **Web games page:** [Daniel's Games](https://sites.google.com/view/danielsgxmes/games)

---

*Made to make Heaven for Death easier to play in a browser. Have fun!* 
