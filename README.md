# hourlyWeatherDemo
Hourly Weather Demo

Requires AccuWeather API Key. You can get your API Key at https://developer.accuweather.com

## How to display the fields in the ViewBox

The ViewBox does not populate the fields initially because the API key is stored as a session variable, set in the ```onDialogInitialize``` event, which is not executed when the Xbasic function to populate the ViewBox from the ViewBox Builder. You can get the ViewBox to populate the fields by setting the default value for the ```apikey``` variable in the Xbasic functions to your API key. **Note:** There are mulitple instances of the ```apikey``` Xbasic variable. Make sure to update all of them.
