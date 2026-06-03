# Atmosphera Weather Intelligence
Atmosphera is a weather application built using HTML, CSS, and vanilla JavaScript. I wanted to create something that feels more premium than a typical weather app, so I focused heavily on the UI/UX while keeping the codebase simple. 
The app allows users to search for any city and instantly view live weather conditions, including temperature, humidity, wind speed, visibility, UV index, pressure, cloud coverage, air quality, and local time. Weather data is fetched in real time using the WeatherAPI service.

-> Built with:
HTML5
CSS3
JavaScript (ES6)
WeatherAPI

-> How It Works:
The application sends a request to the WeatherAPI endpoint whenever a user searches for a location. Once the data is received, JavaScript dynamically updates the UI with the latest weather information.
A loading state is displayed while data is being fetched, and meaningful error messages are shown if something goes wrong.

-> Features:
Search weather by city name
Real-time weather updates
Air Quality Index (AQI) information
Temperature and "feels like" readings
Humidity, wind speed, pressure, visibility, and UV index
Dynamic weather icons
Responsive design for mobile and desktop
Smooth animations and glassmorphism-inspired interface
Error handling for invalid locations or API failures
