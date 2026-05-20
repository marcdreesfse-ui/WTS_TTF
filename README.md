This is the repo which WanderStuck Translator (WST) automatically downloads on its first startup.

This repo contains 3 files:
> font_version.json | This file is used to give WST the infos for the .ttf and .pth file. It's compared with this repo's .json file to auto-update WST in-case the .ttf or .pth files get updated.

> wanderstuck.ttf   | This file contains all wanderstuck language glyphs which are used to correctly display the characters in WST.

> ws_classifier.pth | This file contains all training data for the Custom OCR that comes with WST. it is crucial for the OCR's function
