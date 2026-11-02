# Foodies Map Visual Interactive MVP

A mobile-first standalone app using the **exact generated mockup as the interface artwork**, with transparent interactive hit areas aligned to the image's 941 × 1672 coordinates. No framework or npm install required.

## Run
Open `index.html` in a modern browser, or run `python3 -m http.server 8000` from this folder and visit http://localhost:8000.

## Deploy GitHub → Vercel
Create repository `foodies-map-visual`, upload `index.html`, `design.png`, `manifest.webmanifest`, `vercel.json`. Import into Vercel. Framework Preset: **Other**; Build Command: **leave blank**; Output Directory: **.**; Root Directory: **./**. No environment variables.

## Scope and limitations
Functional city tabs, category buttons, search, sample place detail, OpenStreetMap city map, camera/file picker, star rating, review form, device-local demo votes, rankings, favorites, recipes and pairing, bottom navigation. The original London artwork remains unchanged when switching city; overlays provide the selected city data. Images and listed venues are illustrative and not verified. No backend, social data ingestion, real rankings, actual photo validation, or real user verification. Photos are not stored or uploaded. The design art must not be presented as real venue photography. Image crop hotspots use percentage coordinates; the full original image is displayed without cropping.
