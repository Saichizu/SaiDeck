# SaiDeck

SaiDeck is a single-file, BandLab-style multitrack editor that turns a song's vocal and instrument tracks into a vertical music video, rendered straight to MP4 in the browser.

## Use it

Download `SaiDeck.html` and open it in Chrome or Edge. Everything runs on your own computer; nothing is uploaded.

## Updates

SaiDeck checks this repository for a newer version. When one is ready, the update button at the top lights up. Click it and choose **Update now**. The new version is saved over your file, and the old one is kept as `… (before update).html`.

`version.json` holds the newest build number. Each published version raises `build` by one, matching `SD_BUILD` inside `SaiDeck.html`.

## Freedits

Freedits (render styles) are separate `.saifreedit` files. Put them in a `Freedits` folder next to your project and press **Refresh** in Render › Freedit.
