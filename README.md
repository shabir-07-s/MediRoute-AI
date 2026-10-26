# MediRoute AI — Working Front-End Prototype

## What works
- Responsive web UI for desktop and mobile.
- Interactive OpenStreetMap/Leaflet map.
- Eight clearly labelled **sample demo records** around Chennai.
- Search by name, area, or listed service.
- Filter by service and sort by approximate straight-line distance or name.
- Browser geolocation (permission required) and map recentering.
- External route links to OpenStreetMap.
- Basic accessibility labels and mobile layout.

## Important limitations
- This is a front-end prototype, not a deployed medical service.
- The hospital records, phone numbers, and services are fictional demo data. Do not call them or rely on them.
- Live bed availability, ambulance status, emergency capacity, and hospital data integrations are not implemented.
- GPS can locate the user anywhere, but the sample hospitals are only around Chennai; the app warns about this.
- The "best match" ranking is a transparent simple rule-based sort, not a trained AI model. The project name describes the concept; do not claim AI prediction has been implemented.
- Internet is required for Leaflet, OpenStreetMap map tiles, and route links.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser. If browser geolocation does not work from a local file, serve the folder over localhost (for example with VS Code Live Server or `python -m http.server 8000`) and open `http://localhost:8000`.
3. Replace sample data only with verified, permitted data sources before real-world use.

## Suggested next development steps
1. Replace sample records with verified hospital directory data and add source/last-verified fields.
2. Add backend API and database, validation, and an admin update workflow.
3. Add service verification and safe fallback for unavailable data.
4. Test usability with realistic scenarios and document limitations.
5. Record a demo video showing search, service filter, distance ranking, map marker, and route link.
