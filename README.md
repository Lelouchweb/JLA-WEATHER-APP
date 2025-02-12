# JLA-WEATHER-APP
The Weather App is a web-based application that displays real-time weather data for a specific city. Users can enter a city name, and the application will fetch and display relevant weather data, such as temperature, humidity, wind speed, pressure, and sunrise/sunset times. The app uses the OpenWeatherMap API to dynamically locate weather data.

The layout consists of three major sections:
- Top Section: Contains the city entry field, day, date, and time.
- Middle Section: Shows the current weather status and an image depicting the weather situation.
- Bottom Section: Displays weather information including temperature, wind speed, humidity, 
and air pressure.
Animations and transitions have been employed to improve the visual appeal, resulting in a 
seamless and modern UI/UX experience.

API Integration
To fetch real-time weather data, the application integrates the OpenWeatherMap API. The 
API request is triggered when a user inputs a city name and presses the 'Enter' key. The following 
API endpoint is used
`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=b8de89f0ac112646fc9bb5
3ff48fe824&units=metric`);

The API Integration Process: 
1. The user enters a city name. 
2. A JavaScript function sends an XMLHttpRequest to fetch data from the OpenWeatherMap 
API. 
3. If the request is successful, relevant weather details are retrieved and displayed.
4. If the request fails (e.g., city not found), an error message is displayed.

The API response includes data on:
- Temperature (current, minimum, and maximum)
- Wind speed
- Humidity and pressure levels
- Sunrise and sunset times
- Weather description and icon
  
User Interactions
The application provides a user-friendly interface with the following interactions:
City Input: Users can type the name of a city, and pressing 'Enter' triggers the API call.
Dynamic Weather Updates: The displayed weather data updates automatically based on the 
specified city.
Animated background: The background animates gradually to produce a smooth visual 
appearance.
Interactive Elements: The time on the display expands when it remains, and weather images 
change dynamically based on API responses.
The combination of these elements provides a smooth and interesting user experience.

Conclusion
The WeatherApp successfully integrates real-time weather data from the 
OpenWeatherMap API, displaying it in an animated and nice style. Overcoming a few challenges 
helped us gain a better understanding of API integration, JavaScript event handling, and UI/UX 
design concepts.
