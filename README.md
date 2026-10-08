# Tomato Timer

A Pomodoro timer for phone and desktop: 25-minute focus sessions, 5-minute short breaks, and a long break after every four.

**Live:** https://raysantos.github.io/tomato-timer/

## Features
- Kitchen-timer dial that changes color by mode (focus, short break, long break)
- Chime at the end of each session, optional auto-start
- Adjustable durations, saved per device
- Daily count of pomodoros and minutes focused
- Light/dark toggle
- Installable as an app with the tomato icon; works offline
- Keyboard: Space start/pause · R reset · S skip

## Install
- **iPhone:** open the link in Safari → Share → Add to Home Screen
- **Android / Chrome desktop:** open the link → Install app (address bar icon or ⋮ menu)

## Files
- `index.html` – the whole app (HTML, CSS, JS)
- `manifest.webmanifest`, `sw.js` – install and offline support
- `icons/` – tomato icon (SVG source + PNGs)

After editing files, bump `VERSION` in `sw.js` so installed copies pick up the change.
