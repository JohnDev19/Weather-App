# Weather App

This Weather App is a simple and user-friendly application that allows users to search for the current weather conditions in any city. It provides real-time weather updates including temperature, humidity, wind speed, and atmospheric pressure. The app also allows users to switch between Celsius and Fahrenheit units.

![image](https://github.com/JohnDev19/Weather-App/assets/137758073/53a7e7c5-4f57-4f6c-9257-8f5b9c38ec21)


## Features

- **Search Functionality**: Users can search for the weather in any city.
- **Unit Conversion**: Switch between Celsius and Fahrenheit.
- **Real-time Weather Data**: Displays current weather conditions including temperature, real feel, humidity, wind speed, and atmospheric pressure.
- **Responsive Design**: Adjusts to various screen sizes for optimal user experience.
- **Dynamic Icons**: Weather icons change based on the current weather conditions.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling of the application.
- **JavaScript**: Functionality and interactivity.
- **OpenWeather API**: Fetching real-time weather data.

## How to Use

1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project directory.
   ```bash
   cd weather-app
   ```
3. Open `index.html` in your browser to run the application.
   ```bash
   open index.html
   ```

## File Structure

```
weather-app/
│
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
├── script.js           # JavaScript file for functionality
└── README.md           # Documentation file
```

## Code Explanation

### HTML (index.html)

The HTML file sets up the structure of the application, including the search form, units toggle, and sections for displaying weather data.

### CSS (style.css)

The CSS file styles the application, ensuring a clean and modern look with responsive design principles.

### JavaScript (script.js)

The JavaScript file handles the logic of fetching weather data from the OpenWeather API, updating the DOM with the received data, and managing unit conversion.

## Future Enhancements

- **Weather Forecast**: Extend the app to show a 5-day weather forecast.
- **Geolocation**: Automatically detect user's location and display weather.
- **Improved UI**: Enhance the user interface with more detailed weather information and better design.

## API Key

This project uses the OpenWeather API. To run the project, you will need an API key from OpenWeather. You can get one by signing up on their website: [OpenWeather](https://openweathermap.org/).

Replace the placeholder API key in `script.js` with your actual API key:
```javascript
const API_KEY = 'your_api_key_here';
```

## License

This project is licensed under the MIT License.

## Acknowledgements

- [OpenWeather](https://openweathermap.org/) for providing the weather data API.
- [FontAwesome](https://fontawesome.com/) for the weather icons.

---
