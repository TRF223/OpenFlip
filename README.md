<p align="center">
  <img src="logo.jpg" alt="OpenFlip logo" width="240">
</p>

<h1 align="center">OpenFlip</h1>

<p align="center">A flipbook animator inspired by Flipnote Studio. It runs from a single HTML file and has a built-in bitcrusher for sound.</p>

## Features
- 256×192 pixel canvas, two layers, pen / eraser / fill, four colours, four brush sizes
- Fire tool: stamps a pixel flame that flickers differently on every frame
- Onion skin, filmstrip timeline, add / duplicate / clear / delete frames
- Page-flip, slide and fade transitions while you edit (playback always runs without effects)
- Playback from 1 to 24 fps with looping, and PNG export of the current frame
- Sound lab: 14 synthesised effects, mic recording (8 seconds max), audio import and a bitcrusher
- Place any sound on a frame so it plays during playback
- Settings: language (English, Deutsch, Español), theme (auto, light, dark), page effect, volume, advanced mode
- Advanced mode unlocks bit depth, sample rate, dry/wet mix and a crusher on/off switch; with it off the crusher stays at its default
- Works on phones and tablets

## Run it
Open `index.html` in a browser. No build step, no dependencies. Fonts load from Google Fonts with system fallbacks.

Microphone recording needs a secure context (`https://` or `localhost`). If the browser blocks it, use Import audio or Capture instead.

## Shortcuts
Space: play or stop. Left / right arrows: step frames. Ctrl+Z: undo. B / E / G / F: pen, eraser, fill, fire. Esc: close settings.

## Disclaimer
This Project is vibecoded
