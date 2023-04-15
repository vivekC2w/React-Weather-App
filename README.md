React Weather App

This is a responsive weather app built using React, CSS, and JavaScript. It uses two APIs - GeoDB Cities and OpenWeather - to display current weather and forecast data for a user-specified location.

Features

1. Search bar to input location
2. Current weather component displaying current temperature, weather conditions, and location
3. Forecast component displaying a 5-day forecast with high and low temperatures and weather conditions
4. Accordion component to toggle between current weather and forecast views
5. Async pagination to display a dropdown list of location suggestions as the user types in the search bar

APIs Used 1. GeoDB Cities for location suggestions and geocoding 2. OpenWeather for weather data

Dependencies
React: ^17.0.2  
 react-accessible-accordion: ^3.3.0
react-select-async-paginate: ^2.3.0

Installation and Usage 1. Clone this repository: git clone https://github.com/vivekC2w/React-Weather-App.git 2. Install dependencies: npm install 3. Sign up for a free account at RapidAPI to obtain API keys for GeoDB Cities and OpenWeather. 4. Create a .env file in the root directory of your project and add the following environment variables:

    REACT_APP_GEODB_API_KEY=your_geodb_api_key_here
    REACT_APP_OPENWEATHER_API_KEY=your_openweather_api_key_here

    5.  Start the development server: npm start
    6. Open http://localhost:3000 in your web browser to view the app.
