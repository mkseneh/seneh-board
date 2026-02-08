# Seneh Board (Event Countdown Dashboard)

A lightweight, responsive single-page dashboard that renders a live event board
with countdown timers. The UI is designed for clarity on large screens and
automatically switches to a minimal mode on mobile.

## What it does

- Loads event data from a CSV source (e.g., Google Sheets published as CSV)
- Renders a styled table of upcoming events
- Updates countdown timers every second
- Auto-refreshes data periodically
- Applies simple status logic: UPCOMING / NOW / ONGOING / PAST

## What this project demonstrates

- HTML/CSS layout and responsive design
- Clean, readable JavaScript (no frameworks)
- Data fetching and client-side parsing
- DOM rendering and periodic updates
- Practical UI/UX decisions (minimal mobile mode, status badges)

## How to run locally

Because this page fetches CSV data using `fetch()`, some browsers block it when
opening the file directly (`file://`). Run a small local web server instead.

### Option A (recommended): Python built-in server

From the project folder:

```bash
python3 -m http.server 8000
