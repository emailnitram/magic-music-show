# Magic Music Show

A webcam-based hand-tracking visualizer for kids. Move your hands to create particle effects while your favorite songs play.

**Live site:** https://emailnitram.github.io/magic-music-show/

## How to use

1. Open the site on a phone or desktop
2. Allow camera access
3. Tap a song to start playing
4. Move your hands in front of the camera — sparkles, snowflakes, and bubbles trail from your fingertips

## Songs

- ✨ Golden
- 🫧 Soda Pop
- ❄️ Let It Go *(Frozen)*
- ⛄ Do You Want to Build a Snowman? *(Frozen)*

## Running locally

YouTube embeds require the page to be served over HTTP — opening `index.html` directly as a file won't work. Run a local server instead:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080 in Chrome or Edge and allow camera access.

## Tech

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) — real-time hand tracking in the browser
- YouTube IFrame API — audio streaming
- Canvas 2D — particle effects
