# wanderpin 🌍📍

A personal map of your travels — drop pins on the cities you've visited and watch the countries you've been to get painted with their own flag (very subtle).

Single-file app: just open `index.html` in your browser. No install, no build.

## Features

- **City search** with autocomplete (suggestions as you type) — drops a pin with the country's flag.
- **Double-click the map** to drop a point manually.
- **Visited countries** are filled with their own flag as a faint background.
- **Per-country clustering**: crowded pins of the same country merge into a bigger flag bubble with a count.
- **Cross-country declutter**: pins from different countries that overlap push each other apart.
- **Tourist hubs** get a larger pin with a golden ring and a ⭐.
- **Sidebar list** grouped by country, with counters and quick removal.
- Everything is saved in the browser (`localStorage`) — close and reopen without losing anything.

## Usage

Open `index.html` in any browser. Requires an internet connection for the map tiles, city search (Nominatim/OpenStreetMap) and flag images (flagcdn).

## Stack

- [Leaflet](https://leafletjs.com/) + CARTO dark tiles
- [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)
- Geocoding: [Nominatim](https://nominatim.org/) (OpenStreetMap)
- Country borders: [Natural Earth](https://www.naturalearthdata.com/)
- Flags: [flagcdn](https://flagcdn.com/)

## License

MIT
