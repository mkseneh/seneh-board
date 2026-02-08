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

1. Open `index.html` in a browser.

For live data, set the CSV URL in the config section:

```js
const CSV_URL = "YOUR_CSV_URL_HERE";
