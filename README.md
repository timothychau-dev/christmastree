# Interactive 3D Christmas Tree

A gesture-controlled 3D Christmas tree built with Three.js. Control it with your hands, face, and voice — upload photos as ornaments, and trigger a party mode with a clap.

## Features

- Hand gestures: open hand scatters ornaments, V-sign enters tree mode, pinch zooms
- Face tracking: smile snaps a webcam photo onto an ornament
- Audio: clap triggers party mode
- Upload your own photos as double-sided ornaments
- UnrealBloom glow, falling snow, procedurally generated star and ornaments
- Preloader with audio-unlock, idle reset, party-mode countdown

## Run locally

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open http://localhost:8000 (webcam + microphone permission required)

## Tech

- Three.js, MediaPipe Hands / Face Detection / Audio Classifier
- Vanilla JavaScript

## Note

Webcam and audio features require a secure context (localhost or HTTPS).
