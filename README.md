# SHOKH HUB v3.1 — Repair release

This is a bug-fix release, not a new product. Maintains v3 features and v2-compatible localStorage keys.

## Deployment to GitHub Pages
Upload **index.html, style.css, app.js, hub-banner.jpg** into the root of the `main` branch. In Settings → Pages select main / (root). Open https://hirokasimov.github.io/Test-branch/ after deployment succeeds. Force refresh if a cached old page persists.

The `index.html` includes an inline copy of the JS, so even if `app.js` is accidentally missing on Pages the interface still boots. `app.js` is included separately for maintainability; edit both when changing the app logic.

## Changes
- Six colorful module cards and initial project shortcuts have HTML fallback (no blank page if JS fails).
- Inline JS removes dependency on loading app.js at runtime.
- Error notice shows uncaught script errors instead of silently leaving blank panels.
- Mobile tiles are visible in a 2-column grid, with stronger neon and tighter spacing.
- Tasks have a designed empty state.
- No fake live network analytics: wave is decorative.

## Limitations
Live project widgets use local HUB data only; external sites are not connected. Notifications require permission and the HUB tab to remain open. Privacy mode is visual masking, not authentication or encryption. Browser end-to-end validation could not be completed in this environment.
