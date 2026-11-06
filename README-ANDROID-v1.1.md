# ATLAS Android v1.1 — TRACE Record / Stop Update

This update is for the existing **ATLAS-ESTIMATING-ANDROID-COMPLETE** version.

## New field workflow

- The visible **WALL** button is hidden.
- The old **LOCK** button is hidden because TRACE now controls recording.
- **TRACE ▶** starts recording a wall chain.
- While recording, the same button becomes **STOP ■**.
- Press **STOP ■** to finish the current chain.
- Press **TRACE ▶** again to begin a brand-new disconnected chain.
- The currently selected wall type remains active, so the new section uses the same wall type until you change it.
- **ORTHO** remains available and unchanged.
- When TRACE is off, the drawing is in normal wall-selection mode, so you can still select existing walls.

This uses ATLAS's existing internal trace and wall-selection actions. Quantity calculations, saved projects, wall types, doors, materials, and takeoff formulas are not changed.

## Update your published Android site

Replace these Android-specific files in the published Android repository:

- `android.html`
- `sw-android.js`

The ZIP also includes the existing Android manifest/icons for convenience.

After uploading:
1. Open `android.html` in Chrome while online.
2. Fully close the installed ATLAS Android app.
3. Reopen ATLAS.
4. If the old toolbar is still cached, refresh `android.html` once in Chrome, then reopen the installed app.
