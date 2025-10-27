# Weather Dashboard

A modern, responsive weather dashboard web app that allows users to search for any city and view the current weather and a 5-day forecast. 

## Features
- Search for any city and get real-time weather data
- Displays current weather (temperature, humidity, wind, pressure, etc.)
- 5-day forecast with weather icons and subtle color tints
- Animated gradient background for a modern look
- Smooth card hover and fade-in animations
- Responsive design for desktop and mobile
- Error and loading states for better UX

## Tech Stack
- HTML, CSS (Tailwind, custom styles)
- JavaScript (vanilla)
- [Open-Meteo API](https://open-meteo.com/) (free, no API key required)

## Setup & Usage
1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Start a simple HTTP server (Python example):
   ```sh
   python -m http.server 8000
   ```
4. Open your browser and go to [http://localhost:8000](http://localhost:8000)
5. Enter a city name and view the weather!

## Notes
- The focus was on delivering a clean, functional, and visually appealing solution within a short timeframe.
- The app uses the free Open-Meteo API which requires no API key and provides reliable weather data.

## Screenshots
![screenshot](screenshot.jpg)

---
Feel free to use or extend this project!

## API

The Weather Dashboard uses the [Open-Meteo API](https://open-meteo.com/) to fetch the weather data. This is a free API that requires no registration or API key, making it easy to use and deploy.

## Contributing

If you would like to contribute to the Weather Dashboard project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request to the original repository.


## Testing

To test the Weather Dashboard, simply open the `index.html` file in a web browser and interact with the application. Ensure that the search functionality, current weather display, and 5-day forecast work as expected.



