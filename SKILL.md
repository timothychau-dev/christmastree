---
name: christmastree
description: Gesture-controlled 3D Christmas tree (hands, face, clap). Use to run locally; requires webcam and mic.
---

# christmastree

Interactive 3D Christmas tree controlled by hand gestures (open hand, V-sign, pinch), face tracking (smile photo), and clap detection (party mode). Upload photos as ornaments.

## Quick commands

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

Requires webcam + microphone and a secure context (localhost counts).

## Conventions

- Single-page app: `index.html` (Three.js + MediaPipe via CDN).
- External deps: Poly Haven HDR + Google-hosted MediaPipe models (fine to keep).
- Audio unlock flow: user click unlocks WebAudio.

## Verification

- Gesture tests need a real camera; at minimum verify the page loads, preloader completes, and the tree renders.
