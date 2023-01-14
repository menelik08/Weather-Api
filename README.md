# Weather-Dashboard

## Description 

 The application uses [OpenWeather API](https://openweathermap.org/api) to pull weather and forecast informaton for cities across the US and provides updated weather data and forecasting. 

Enter in your city of choice and select search to view the current weather and forecast for the next five(5) days.
The webpage is easy for you to access through one link.

## Webpage Preview 

![screenshot](./assets/images/weather%20dashboard.png)

## Features 

- Searched for a city, the current and future conditions for that city will be presented and that city is added to the search history
- The current weather conditions for the city including:
    - City name
    - Date
    - An icon representation of weather conditions
    - Temperature
    - Humidity
    - Wind speed
    - UV index
- The UV index is presented with a color indicating severity (reference: https://en.wikipedia.org/wiki/Ultraviolet_index)
    - 🟩  0-2 Low
    - 🟨  3-5 Moderate
    - 🟧  6-7 High 
    - 🟥  8-10 Very High
    - 🟪  11+ Extreme
- 5-day forecast will be presented with the following information:
    - Date
    - An icon representation of weather conditions
    - Temperature
    - Humidity
- When a city in the search history is clicked, the current and future conditions for that city is presented again
- When the weather dashboard is opened, the last searched city forecast is presented

