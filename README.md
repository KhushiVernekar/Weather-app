### Weather Forecast App
This app uses http://openweathermap.org/ api to fetch the data

This is web-app created in angular.js for the demonstration purpose.

#### How to run
Clone the app with 
`git clone --recursive https://github.com/aks-/weather_forecast_app; cd weather_forecast_app`

You can run this app with any server, you could use something like vscode
server


#### Usage
* It uses geolocation services to find the location, allow browser to find location by clicking 'Allow'.
* It will show you the weather forcast for 7 days (You can change the count of days by going to services/WeatherService.js and change it on line 3.
* On entering the new city names it will open the new tab with the weather data without reloading the page.
