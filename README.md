# 🌦️ Weather App

A responsive weather app built with **HTML, CSS and vanilla JavaScript** that shows live weather using the [OpenWeatherMap API](https://openweathermap.org/api).

## Features
- **Your Weather:** detects your location (Geolocation API) and shows the local weather
- **Search Weather:** look up the current weather for any city
- Shows temperature, weather description and icon, wind speed, humidity and cloudiness
- Shows the country flag (via flagcdn.com)
- Loading screen while data is fetched
- Remembers your coordinates for the session (`sessionStorage`)

## Tech Stack
- HTML5
- CSS3 (Flexbox, Google Fonts – Merriweather Sans)
- JavaScript (ES6+, `async/await`, Fetch API)
- OpenWeatherMap Current Weather API

## Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/aakashcse/weather-app.git
   ```
2. Open the folder in VS Code.
3. Install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.
4. Allow location access, or use the **Search Weather** tab.

> Live Server (or any `localhost` server) is recommended because browsers may block location access on pages opened directly from a file.

### API Key
The app uses an OpenWeatherMap API key in `index.js` (`API_KEY`). You can get your own free key at [openweathermap.org](https://openweathermap.org/api) and replace it.

## Project Structure
```
weather-app/
├── index.html
├── styles.css
├── index.js
└── assets/        # icons, loader and images
```

## Author
**Aakash Kumar Singh** · [GitHub](https://github.com/aakashcse)
