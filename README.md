# Weather App

## Overview

This Weather App was developed as a project during my college studies to explore and learn about APIs. The app retrieves real-time weather data from a public API and displays it to users in a user-friendly interface. The project served as a hands-on approach to understanding how APIs work, how to integrate them into a frontend application, and how to handle asynchronous data fetching in JavaScript.

## Features

- **Real-Time Weather Data**: Fetches and displays current weather information for any City or State.
- **Temperature Display**: Shows temperature in both Celsius.
- **Weather Conditions**: Displays additional information such as humidity, wind speed, and weather conditions (e.g., sunny, cloudy, rainy).

## Technologies Used

- **React**: The app was built using React, a popular JavaScript library for building user interfaces.
- **Tailwind CSS**: For styling the application, Tailwind CSS was used to ensure a clean and responsive design.
- **OpenWeatherMap API**: The app uses the OpenWeatherMap API to fetch real-time weather data.
- **JavaScript (ES6+)**: Modern JavaScript features were used to manage state and handle API requests.

## Installation

1. **Clone the Repository**:

2. **Install Dependencies**:
    Ensure you have Node.js installed, then install the necessary packages:
    ```bash
    npm install
    ```

3. **Run the App**:
    Start the development server:
    ```bash
    npm start
    ```
    The app should now be running on `http://localhost:3000`.

## Usage

1. **Search for a City**:
   - Enter the name of the city in the search bar to retrieve the current weather data.

2. **View Weather Information**:
   - The app will display the temperature, weather conditions, humidity, and wind speed for the selected city.

3. **Switch Temperature Units**:
   - You can toggle between Celsius and Fahrenheit to view the temperature in your preferred unit.

## Learning Outcomes

Through this project, I gained a deep understanding of:

- **API Integration**: How to connect a frontend application to a third-party API, handle API keys, and manage asynchronous data.
- **State Management**: Using React's state management to handle dynamic data and re-render components efficiently.
- **Error Handling**: Managing errors gracefully when API requests fail or when user input is invalid.

## Potential Improvements

- **Weather Forecast**: Extend the app to provide a multi-day weather forecast (past friday).
- **Geolocation Support**: Automatically detect the user's location and display local weather.
- **Historical Data**: Add functionality to view historical weather data.
- **Enhanced UI/UX**: Improve the user interface with additional animations, themes, or a more interactive design.

## Acknowledgements

- Thanks to [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- Special thanks to my college instructors and peers who provided guidance and feedback during this project.


