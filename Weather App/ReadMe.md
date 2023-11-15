# Weather App

A simple web application that allows users to search for weather information of a specific city.

## Description

The Weather App is a user-friendly web application that enables users to retrieve weather information for a given city. The application displays the current weather conditions, temperature, and other relevant weather data.

## Features

- User-friendly interface.
- Real-time weather data.
- Displays current temperature and weather conditions.
- Uses OpenWeatherMap API to fetch weather data.


## Usage

1. Open the `index.html` file in a web browser.
2. Enter the name of the city you want to check the weather for in the input field.
3. Click the "Search" button.
4. The weather information for the specified city will be displayed on the page.

## Installation

There is no installation required for this application. Simply open the `index.html` file in a web browser to use the app.

## APIs Used

- [OpenWeatherMap API](https://openweathermap.org/api) - Used to retrieve weather data for the specified city.

## Files and Directory Structure

- `index.html`: HTML structure of the app.
- `style.css`: Stylesheet for the app.
- `key.js`: JavaScript file containing API key (not provided in this repository).
- `script.js`: JavaScript code for fetching and displaying weather data.
- `weather_app_preview.png`: Preview image of the Weather App (replace with your own screenshot).

## Acknowledgements

- Fonts from [Google Fonts](https://fonts.google.com/).
- Weather data provided by the [OpenWeatherMap API](https://openweathermap.org/api).


## JavaScript Logic (`index.js`)

The `index.js` file contains the JavaScript logic for fetching weather data from the OpenWeatherMap API and updating the UI with the retrieved information.

The script listens for a click event on the search button. When clicked, it retrieves the user-entered city name from the input field and makes a fetch request to the OpenWeatherMap API using the provided API key. The fetched JSON response is then processed to display weather information on the page.

The app displays weather conditions based on the received weather data, such as temperature, description, humidity, and wind speed. The app also handles cases where the city is not found, displaying an error message.

## Images

The `images` directory is referenced in the JavaScript code for displaying weather icons based on weather conditions. Make sure to have corresponding image files (`clear.png`, `rain.png`, `snow.png`, `cloud.png`, `mist.png`, etc.) in the `images` directory.

## Note

- Replace `'Your Api Key'` in the JavaScript code with your actual OpenWeatherMap API key.
- Ensure that your API key is stored securely and is not exposed in a public repository.

## Contributing

Contributions to this project are welcome! Feel free to open issues and submit pull requests if you have any improvements or suggestions.


## Acknowledgements

- Weather data provided by the [OpenWeatherMap API](https://openweathermap.org/api).
- Weather icons used in the app are for illustration purposes and are not included in this repository.

## API Key (`key.js`)

The `key.js` file contains your OpenWeatherMap API key. This key is necessary to access weather data from the OpenWeatherMap API. The API key is assigned to the variable `key`.

**Important:** Ensure that you keep your API key secure and do not expose it publicly. It's recommended to use environment variables or other secure methods to manage your API keys, especially if you're sharing your code in a public repository.

```javascript
//Assign the copied API key to the 'key' variable
key = "ba4b8b22c1f75476f1a6fa609e8befed";


## JavaScript Logic (`script.js`)

The `script.js` file contains additional JavaScript logic to fetch weather data from the OpenWeatherMap API and display it on the web page.

The script defines a function `getWeather()` that fetches weather details based on the user-entered city name. The function makes use of the provided API key (`key`) and the OpenWeatherMap API to retrieve weather data.

The script handles cases where the city name is either valid or not found. It updates the HTML content of the `result` element to display relevant weather information, including the city name, weather conditions, description, temperature, and temperature range.

The script also adds event listeners to the search button and the window's `load` event to trigger the `getWeather()` function when the button is clicked or when the page loads.

## Note

- The `key` variable in this script is expected to be provided by the `key.js` file.

## Contributing

Contributions to this project are welcome! Feel free to open issues and submit pull requests if you have any improvements or suggestions.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Weather data provided by the [OpenWeatherMap API](https://openweathermap.org/api).
- Weather icons used in the app are for illustration purposes and are not included in this repository.


--------------

# Weather App

A simple web application that allows users to search for weather information of a specific city.

## Description

The Weather App is a user-friendly web application that enables users to retrieve weather information for a given city. The application displays the current weather conditions, temperature, and other relevant weather data.

## Features

- User-friendly interface.
- Real-time weather data.
- Displays current temperature and weather conditions.
- Uses OpenWeatherMap API to fetch weather data.

## Preview

![Weather App Preview](weather_app_preview.png) <!-- You can replace this with an actual screenshot of your app -->

## Usage

1. Open the `index.html` file in a web browser.
2. Enter the name of the city you want to check the weather for in the input field.
3. Click the "Search" button.
4. The weather information for the specified city will be displayed on the page.

## Installation

There is no installation required for this application. Simply open the `index.html` file in a web browser to use the app.

## APIs Used

- [OpenWeatherMap API](https://openweathermap.org/api) - Used to retrieve weather data for the specified city.

## Files and Directory Structure

- `index.html`: HTML structure of the app.
- `style.css`: Stylesheet for the app.
- `key.js`: JavaScript file containing API key (not provided in this repository).
- `script.js`: JavaScript code for fetching and displaying weather data.
- `weather_app_preview.png`: Preview image of the Weather App (replace with your own screenshot).

## JavaScript Logic (`script.js`)

The `script.js` file contains additional JavaScript logic to fetch weather data from the OpenWeatherMap API and display it on the web page. The script handles cases where the city name is either valid or not found, updating the HTML content accordingly.

## API Key (`key.js`)

The `key.js` file contains your OpenWeatherMap API key. Make sure to keep your API key secure and not expose it publicly.

## Styles (`style.css`)

The `style.css` file contains styling rules for the Weather App. It defines the layout, colors, fonts, and animations used in the app's interface.

## Note

- Replace `'Your Api Key'` in the JavaScript code and `"ba4b8b22c1f75476f1a6fa609e8befed"` in the `key.js` file with your actual OpenWeatherMap API key.

## Contributing

Contributions to this project are welcome! Feel free to open issues and submit pull requests if you have any improvements or suggestions.


## Acknowledgements

- Fonts from [Google Fonts](https://fonts.google.com/).
- Weather data provided by the [OpenWeatherMap API](https://openweathermap.org/api).
- Weather icons used in the app are for illustration purposes and are not included in this repository.
