## Weather App: Get Real-Time Weather Information

This README.md file provides an overview of a simple weather app that allows users to search for real-time weather information for any location.

### Features

* **Search Functionality:** Users can enter a city or click on the location icon to get the weather updates of user's current location.
* **Weather Data Display:** Relevant weather details are displayed, including:
    * City
    * Current Temperature (°C)
    * Weather Description (e.g., Sunny, Cloudy, Raining) with the help of icon
    * Humidity (%)
    * Wind Speed (m/s)
    * Pressure (hPa)
    * Visibility (Km)
    * Feels Like
    * Today's Weather At Different Time's
* **Weather Icon:** A visual representation of the current weather conditions using an icon.

### Technologies Used

* **HTML:** Defines the structure and content of the app's user interface.
* **CSS:** Styles the HTML elements for visual appeal (fonts, colors, layouts, effects).
* **JavaScript:** Handles interactivity and data fetching:
    * Retrieves weather data from an API based on user input.
    * Updates the UI with the retrieved weather information.

### API Integration

The app utilizes the OpenWeatherMap API to fetch weather data. You'll need to obtain your own API key from [https://openweathermap.org/appid](https://openweathermap.org/appid). Replace `YOUR_API_KEY` in the code with your actual key.

### Folder Structure

The app consists of the following files within a single directory:

* `index.html`: The main HTML file that defines the app's structure.
* `style.css`: The CSS file that styles the HTML elements.
* `script.js`: The JavaScript file that handles data fetching and UI updates.

### Deployment

You can deploy the app to:

* A web server for public access.
* A platform like GitHub Pages for hosting (requires basic HTML knowledge).

### Usage

1. **Clone this repository:**
   ```bash
   git clone https://github.com/TheCodeWiz/Weather-app.git
   ```
3. Replace `YOUR_API_KEY` in `script.js` with your OpenWeatherMap API key.
4. Open `index.html` in a web browser to use the app.

### Future Enhancements

* **Additional Weather Details:** Include precipitation, sunrise/sunset times, and UV index.
* **Weather Forecast:** Provide a multi-day weather forecast.
* **Offline Mode:** Explore caching weather data for limited offline functionality.
* **Customization:** Allow users to personalize the app's appearance and behavior.
* **Mobile Responsiveness:** Ensure the app adapts to different screen sizes.