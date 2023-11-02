# Weather App 
# Project Description
The Weather App is a web application that allows users to check the current weather conditions for a specific location. It also access users current location coordinates and displays 
weather of his/her particular location. It uses HTML, CSS, and JavaScript to create the user interface and fetches weather data from a third-party API to display the information on the screen.
# Features
1. Input a location (city) to get the current weather information.
2. Display current temperature, weather conditions, and location.
3. Use icons to represent weather conditions (e.g., sunny, rainy, cloudy).
4. Display additional information such as humidity, wind speed, and cloudiness.
5. Displays loader on screen till the data is visible to user.
6. Also asks to grant access to current location so that weather of current location is displayed.
7. Four different parameters created to display one at a time and making other inactive.
# API
This project uses a third-party weather API to fetch weather data. You need to sign up for an API key and replace 'API_KEY' in the config.js file with your actual API key.
You can obtain an API key from Open Weather API. You can sign in for free and get api key.
API - https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${API_KEY}&units=metric`
In this project user coordinates are stored in session storage also. Html, css and javascript used.
