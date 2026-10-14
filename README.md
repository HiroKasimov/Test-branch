# SHOKH HUB v2

Responsive personal project hub based on the user's cyberpunk reference.

## Run
Open `index.html` in a browser, or serve the directory via `python -m http.server 8000` and visit `http://localhost:8000`.

## v2 upgrades
- Neon hover effects and animated ambient lighting (respects reduced-motion preference)
- Time-aware anime banner tint (morning / afternoon / evening / night), based on device local time
- Mobile search button and optimized navigation
- Drag-and-drop module and project ordering, saved in localStorage; touch long-press supported (browser-dependent)
- Browser-local status: online/offline signal, connection type when available, local storage availability, device time. This is **not** external project uptime monitoring.

## Existing functionality
Six original project URLs, project add/filter/search, notes, tasks, Pomodoro, theme, JSON export/import, visit history.

## Data
Existing localStorage keys for notes, tasks and visits are preserved. Browser-local data does not automatically sync across devices.

## Note
`hub-banner.jpg` is a crop from the provided reference image, so some text/artifacts may be visible. Replace with a clean licensed artwork for best quality.
