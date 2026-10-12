# Paper Toss Web AR

This is a WebAR Game using the [A-Frame](https://aframe.io/) and [Three.js](https://threejs.org/)

The game is about throwing a scrunched paper to a trash bin.

## Guide
1. Open the HTTPS URL on a supported Android phone/browser and tap the menu icon at the bottom to open the controls.
2. Tap **Start AR Camera**, allow the browser/AR permission prompts, select **Floor (estimated)** or **Table (~75 cm)**, aim down until the estimated ring appears, then tap **Place the bin**.
3. Close the drawer by tapping the icon again. Swipe upward from the foreground paper; a successful basket plays the supplied sound.

## Project models
- Trash bin model and texture are in `assets/models/trash-bin/`. Source : [Trash Bin](https://sketchfab.com/3d-models/office-cubical-trash-bin-748c8d90f46b4d8e8b30361729f839ee)
- Scrunched paper model and texture are in `assets/models/scrunched-paper/`. Source : [Scrunched Paper](https://sketchfab.com/3d-models/scrunched-paper-333f89070a2f4d0d8b0b30ebfe67cd06)
- The models' original license files are retained in their folders.

## Audio license
The supplied `yay-sound-fx.mp3` archive includes `Read-NonCommercial.txt`, which states that the sound is licensed for **non-commercial use under CC BY-NC 4.0** and references Free Sounds Library: https://www.freesoundslibrary.com. Keep the attribution/license notice with the project and do not use this audio commercially unless you obtain the necessary permission or replace it with audio licensed for commercial use.
Source : [Yay Sound](https://www.freesoundslibrary.com/yay-sound-fx/)

## Testing
For ease of testing i deployed the WebAR on GitHub Pages : [Paper Toss WebAR](https://678ms.github.io/Paper-Toss-WebAR/)

You can run it in your device yourself by downloading the source code and hosting it on a HTTP/HTTPS Server.
