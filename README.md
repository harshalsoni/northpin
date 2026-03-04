# NorthPin

A single-file location tool built for rural and remote areas in Canada. Uses Plus Codes (Open Location Code) as precise, shareable location references — especially useful where civic addresses don't exist.

## Features

- **Plus Code Generation** — Click the map, use GPS, or enter coordinates to generate a 10-digit Plus Code
- **911 Civic Address Checker** — Warns when a location lacks a dispatchable civic address
- **Emergency Location Card** — Print-ready card with Plus Code, GPS, address, and embedded map
- **What3Words Link** — Quick link to the What3Words equivalent for any pinned location
- **Elevation Display** — Shows elevation above sea level via Open-Meteo API
- **Distance Between Points** — Haversine distance and compass bearing between two pins
- **Share via Link** — URL hash-based sharing that auto-loads the pinned location
- **QR Code Generator** — Downloadable QR code linking to plus.codes
- **Copy Formatted Card** — One-click copy of a text summary with Plus Code, GPS, address
- **Search by Address** — Forward geocoding to find locations by address
- **Decode Plus Code** — Reverse a Plus Code back to coordinates on the map
- **Nearby Landmarks** — Shows named features within 1 km via OpenStreetMap Overpass API
- **Street / Satellite toggle** — OpenStreetMap and Esri World Imagery layers

## Usage

Open `index.html` in any modern browser. No build step or server required.

## APIs Used (all free, no keys required)

| API | Purpose |
|-----|---------|
| OpenStreetMap Nominatim | Reverse/forward geocoding |
| Open-Meteo | Elevation data |
| Overpass API | Nearby landmarks |
| What3Words URL | Location link (optional API key for inline display) |

## License

GPL-3.0
