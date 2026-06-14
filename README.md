# NYC Field Guide

A Progressive Web App trip planner optimized for **Greenwich St** — daily checklists, progress tracking, custom stops, and JSON export. Works offline after first load.

## Install on your phone

1. Open the live app in Safari (iOS) or Chrome (Android).
2. **iOS:** Share → **Add to Home Screen**
3. **Android:** Menu → **Install app** / **Add to Home screen**

## Run locally

```bash
cd nyc-trip-planner
python3 -m http.server 8080
```

Open `http://localhost:8080` (service workers require localhost or HTTPS).

## Features

- Day-by-day NYC itinerary with checkboxes
- Progress bar and completion celebration
- Add your own tasks per day
- Persisted state via `localStorage`
- Copy full trip status as JSON
- Offline support via service worker

## Tech

Static HTML/CSS/JS — no build step. PWA manifest + service worker for installability and caching.
