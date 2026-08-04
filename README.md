# ISS Tracker & Flight Deck

A real-time ISS dashboard. Track the International Space Station live, watch telemetry update, see astronaut's aboard.

## Features

- Live ISS position tracking on an interactive map.
- Real-time telemetry for latitude, longitude, altitude, velocity, and footprint.
- Active crew list with fallback data.
- Pass predictor using browser geolocation.
- Audio stream controls for mission-style ambience.(May fail)


---

## Tech Stack

- HTML
- CSS
- JavaScript
- Leaflet.js
- Tailwind CSS
- Public ISS data sources

## Usage

Open the project in your browser and let the dashboard load the live ISS data.

- The map shows the current ISS position.
- The telemetry panel updates live.
- The crew section shows who is aboard.
- The pass predictor estimates when the ISS may be visible from your location.
- The audio section lets you toggle mission-style sound.

If browser location access is allowed, the pass predictor can use your coordinates automatically.

---

## How It Works

The app fetches live ISS position data on a timer and updates the map marker, orbit trail, and telemetry blocks together. Crew data is loaded with fallback handling, and the pass calculator uses the current ISS position plus your location to estimate visibility.

---

## Project Status

Version 1 is complete and ready to ship.

This is the flight-deck version of the project. A denser Bloomberg-terminal-style version is planned later as a separate evolution of the same idea.

---

## AI Declaration

This project was primarily planned, written, and built by me. AI assistance was used as a support tool to help clean up code, debug issues, consolidate layout and styling, and remove dead code while merging different parts into one coherent project.

---

## Notes

- Some live features depend on external APIs.
- If a feed is unavailable, the interface is designed to degrade gracefully instead of breaking completely.
- This project was built for learning, experimentation, and fun.

---

## Contributing

This is a personal project, but suggestions and improvements are always welcome.

(I write bad README's, Please forgive :(  )

---

## License

MIT License.

---

## Credits

Built with a love for space, dashboards, and the kind of projects that start as an idea and slowly become a small obsession.
