# Santorini Evacuation Route Demo

This project is a responsive evacuation route planning demo for Santorini.

It uses:
- [Leaflet.js](https://leafletjs.com/) for interactive maps
- [OpenRouteService](https://openrouteservice.org/) for route calculation
- Geojson generator: https://geojson.io


## Features

- Find and compare named shelters with capacity and facility details.
- Calculate routes by foot or by car, including distance and estimated travel time.
- Avoid predefined danger zones and ferry segments.
- Use device geolocation or select a precise starting point on the map.
- Share the selected destination and quickly refit or zoom the map.
- Continue to show an estimated direct route if the routing API is unavailable.
- Use an accessible, responsive interface designed for desktop and mobile.

## How It Works

- The app uses the browser's geolocation to find your current position.
- If geolocation fails, you can manually select a location on the map.
- Routes are calculated while avoiding danger zones and ferries if possible.

## Deployment

This project is hosted using **GitHub Pages**.
You can access it here:
➡️ [https://konanast.github.io/your-repository/](#)


## Notes

- The OpenRouteService API key used here is for demonstration purposes.
- In production environments, it is recommended to secure the API key on a backend server.

Temporary API Key 27/04/2025: **5b3ce3597851110001cf62486f7eb4c000634e94b29edb797b397e0e**

API Documentation: https://openrouteservice.org/dev/#/api-docs


## License

This project is open-source and free to use.
