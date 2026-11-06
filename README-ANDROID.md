# ATLAS Estimating v2.4 — Android Complete

This folder is the Android-only version of ATLAS Estimating.

It contains the full estimator plus the Android launcher. The iPad files are intentionally not included.

## Main files

- index.html
- app.js
- style.css
- quantities.js
- door-sketch.js
- android.html
- manifest-android.webmanifest
- sw-android.js
- atlas-android-192.png
- atlas-android-512.png

## Install on Android

1. Publish this folder over HTTPS.
2. In Chrome open `android.html`.
3. Tap INSTALL APP, or use Chrome menu → Install app / Add to Home screen.
4. Open ATLAS once while online so the core files can cache.

## Saved projects

OPEN SAVED appears beside OPEN and uses ATLAS's existing IndexedDB saved-project system.

Saved projects are local to that Android device/browser. Use ATLAS project backups when moving jobs between devices.


## v1.2 — TRACE record / stop

This version moves the behavior into the actual ATLAS source, not the Android wrapper.

- WALL is no longer visible.
- LOCK is no longer visible.
- TRACE ▶ starts recording.
- While tracing, TRACE changes to STOP ■.
- STOP ■ finishes that chain and returns to normal wall selection.
- TRACE ▶ again starts a brand-new disconnected section.
- The active wall type stays selected.
- ORTHO stays selected/unselected exactly as it was.
- Normal wall selection works whenever TRACE is stopped.
