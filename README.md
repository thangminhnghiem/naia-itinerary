# Naia Itinerary

Web app for Naia Hoi An sales to make guest itineraries (Retreat and Mini-Retreat), download them as PNG/PDF,
and copy team briefings (Spa, Yoga, Kitchen, Front desk) for Zalo.

- `index.html` – home screen with the two tools
- `retreat.html` – multi-day retreat itinerary
- `mini.html` – Morning / Sunset mini-retreat
- `sw.js`, `manifest.webmanifest`, icons – lets the site be added to the phone home screen and work offline

Everything you type stays in your own browser. Shared templates are stored on Google through the Naia
Apps Script web app (connect once with the Web App URL and the team key: *My templates → Share with the team*).

Built from the Naia Itinerary Maker files. When a file changes, bump `VERSION` in `sw.js` so phones pick up the new version.
