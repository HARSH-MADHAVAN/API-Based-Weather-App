# API-Based-Weather-App

## Overview
This project is a weather application that provides real-time weather information and a four-day weather forecast for a specified city. The app is built using HTML, CSS, and JavaScript, leveraging the OpenWeatherMap API to fetch and display weather data dynamically.

## Features
- **Real-Time Weather Information**: Displays the current temperature, weather conditions, humidity, and wind speed.
- **Weather Forecast**: Shows a four-day forecast with daily temperature and weather conditions.
- **Responsive Design**: Ensures the app looks great on both desktop and mobile devices.
- **Error Handling**: Alerts the user when a city is not found or when the input is invalid.

## JavaScript Features Used
1. **DOM Manipulation**:
   - Selecting and updating HTML elements dynamically using `document.querySelector` and related methods.
   - Dynamically creating and appending forecast items to the DOM.

2. **Event Handling**:
   - Implementing click and keydown events for the search functionality.
   - Adding interactivity through event listeners for user inputs.

3. **API Integration**:
   - Fetching data from the OpenWeatherMap API using the `fetch` method.
   - Parsing and utilizing JSON data to display weather information.

4. **Date and Time Handling**:
   - Using the `Date` object to format and display the current date.
   - Filtering and formatting forecast dates.

5. **Modular Functions**:
   - Creating reusable functions for API requests, data processing, and DOM updates.

6. **Conditional Rendering**:
   - Displaying different sections based on the state (e.g., showing an error message when the city is not found).

## Learnings
- **API Usage**:
  - Understanding API endpoints and query parameters.
  - Managing API keys securely.

- **JavaScript Best Practices**:
  - Structuring code for readability and reusability.
  - Handling asynchronous operations using `async/await`.

- **Error Handling**:
  - Managing errors gracefully when API responses fail or return unexpected data.

- **UI/UX Improvements**:
  - Designing a user-friendly interface with meaningful icons and labels.
  - Ensuring a seamless user experience by providing feedback during interactions.

- **Responsive Design**:
  - Implementing styles that adapt to various screen sizes using CSS.

## Directory Structure
```
└── HARSH-MADHAVAN-API-Based-Weather-App/
    ├── README.md
    ├── index.html
    ├── script.js
    ├── style.css
    ├── message/
    └── weather/
```
- `index.html`: The main HTML file containing the structure of the app.
- `script.js`: JavaScript file for handling app logic and API integration.
- `style.css`: CSS file for styling the app.
- `message/`: Folder containing images for the "not found" and "search city" messages.
- `weather/`: Folder containing weather condition icons.

## How to Use
1. Clone the repository to your local machine.
2. Open the `index.html` file in any web browser.
3. Enter a city name in the input field and press "Search" or hit "Enter."
4. View the current weather details and the four-day forecast for the specified city.

## Future Improvements
- Extend the forecast to seven days.
- Implement geolocation to auto-detect the user's location.
- Add hourly weather forecasts for more detailed information.
- Improve error messages with detailed descriptions.

## Acknowledgments
- **OpenWeatherMap API**: For providing the weather data.
- **Material Symbols**: For enhancing the visual appeal with icons.

This project is a simple yet effective demonstration of integrating APIs into web applications, suitable for beginners exploring JavaScript and web development.

