# YAMU Call 1 Qualification Console

Live teleprompter script, answer capture, and audit decision engine for YAMU Media's
Call 1 (Strategy Call) qualification. Single self-contained static page — no build step.

## Deploy
Static site. `index.html` is served at the root. On Vercel, import this repo and deploy
with the default settings (framework preset: **Other**, no build command, output = root).

## Notes
- Saved-calls **History** uses the browser's local storage, so it persists per-browser/
  per-device. Use **Export all (.json)** in the History panel to back up or move it.
- Cross-device history sync and GHL auto-pull/write-back require a backend (future phase).
