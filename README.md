# LIFE RPG — Awakening (Version 1)

A personal, mobile-first PWA prototype for iPhone Safari.

## What's included
- Dark anime-RPG-inspired interface
- Six progression paths: Guitar, Excel, Turkish, Physical, Gaming backlog, Films & series
- XP, levels, ranks and path progression
- Optional quests and custom quest creation
- Activity logging with time, XP and reflections
- Milestone notes per path
- Game / film / series backlog
- Seven-day XP chart and activity history
- JSON export/import backup
- Local browser storage

## Run locally
Open `index.html` in a modern browser. For PWA installation and service-worker caching, serve the folder over HTTPS.

## Put it on your iPhone
1. Upload the contents of this folder to a static HTTPS host (for example, a private GitHub Pages repository or a static hosting service).
2. Open the resulting HTTPS URL in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.
4. Open LIFE RPG from its new Home Screen icon.

## Important V1 limitations
- Data is stored locally in the browser on this device. Export backups regularly. Clearing Safari website data can erase it.
- The Quest Master currently provides a starter set of editable quests and a simple contextual note. Live AI quest generation requires a secure server/API integration; never put a private API key in client-side JavaScript.
- This is a first functional prototype, not a polished App Store product. Validate the flow and goals before adding more complexity.
