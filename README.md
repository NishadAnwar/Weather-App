# Weather-App

-- The Weather App is a web-based application that allows users to check the current weather conditions either based on their location or by searching for a city. It provides real-time weather updates using the OpenWeather API and features a user-friendly interface with a clean design.


# How It Works
## Granting Location Access

If the user selects "Your Weather" tab, the app checks for stored coordinates in sessionStorage.
If not available, it asks for location permission.
Once granted, it fetches weather data using latitude and longitude.

## Searching for a City

Users can type a city name and click the search button.
The app fetches weather data using OpenWeather API and displays it.

## Handling API Calls

Uses JavaScript fetch() to retrieve weather data from OpenWeather API.
Shows a loading screen while fetching data.
Displays weather details once data is received.


# Tech Stack

### HTML – Structure of the app
### CSS – Styling and layout
### JavaScript – Functionality and API handling
### OpenWeather API – Fetches real-time weather data
