# Weather App

A simple web application that allows users to check the current weather for a location by making asynchronous requests to a weather API. 
This app provides a user-friendly interface, displays weather data, handles errors gracefully, and allows users to switch between temperature units.

## Features

- **Homepage**: Users can enter a location (city or ZIP code) and click "Get Weather" to fetch weather data.
- **Weather Display**: Current weather conditions are displayed, including temperature, humidity, wind speed, and weather description.
- **Error Handling**: User-friendly error messages guide users when the location is not found or there's an issue with the API request.
- **Unit Selection**: Users can toggle between Celsius and Fahrenheit for temperature units.
- **Optional Geolocation**: Users have the option to use their device's geolocation to fetch weather data for their current location.
- **Styling**: The app is styled for a visually appealing user experience with attention to layout, color scheme, and readability.
- **Responsive Design**: The app is responsive and works well on both desktop and mobile devices.

## Usage

1. Enter a location (e.g., city or ZIP code) in the input field.
2. Select a temperature unit (Celsius or Fahrenheit) from the dropdown.
3. Click the "Get Weather" button to fetch and display weather data.

- Click "Use My Location" to automatically fetch weather data for your current location if geolocation is available.


2. Open `index.html` in your web browser.

## API Integration

This app uses the OpenWeatherMap API to fetch weather data. You need to provide your API key by replacing `'YOUR_API_KEY'` in the `app.js` file with your actual API key.

```javascript
const apiKey = '436cb109c1d2f8dbf7cecadb2d455d56';
