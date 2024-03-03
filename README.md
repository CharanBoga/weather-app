## Weather App

This is a simple weather application built using Python's Tkinter library. It allows users to check the current weather conditions of any location by entering the city name. The application fetches weather data from the OpenWeatherMap API and displays information such as temperature, weather condition, humidity, wind speed, and pressure.

### Features:

- **Real-time Weather Updates**: Get real-time weather updates for any location worldwide.
- **User-Friendly Interface**: The application provides a simple and intuitive interface for users to input the location and view weather details.
- **Dynamic Timezone Display**: Displays the current time based on the selected location's timezone.
- **Error Handling**: Handles invalid entries gracefully and alerts users about incorrect input.
- **Customizable Design**: The app's design elements can be customized easily to fit different preferences.

### Technologies Used:

- **Python**: The core programming language used for development.
- **Tkinter**: Python's standard GUI (Graphical User Interface) library used for building the application's interface.
- **OpenWeatherMap API**: Used to fetch weather data for the provided location.
- **Geopy**: Used for geocoding to obtain latitude and longitude coordinates of locations.
- **Timezonefinder**: Used to determine the timezone of the location.
- **Requests**: Python library used for making HTTP requests to fetch data from APIs.
- **Pytz**: Used for timezone calculations and conversions.

### Usage:

1. Enter the name of the city for which you want to check the weather in the provided text field.
2. Click on the search icon to fetch weather data for the specified location.
3. The application will display the current weather conditions, including temperature, weather description, wind speed, humidity, and pressure.
4. The current time for the specified location will also be displayed.

### Screenshots:

![weather](https://github.com/CharanBoga/weather-app/assets/117650577/4350d71d-6b4c-4525-84bd-a70a1c063a5c)
![w2](https://github.com/CharanBoga/weather-app/assets/117650577/ff52fb5d-1ec1-4a1d-8f2e-d4765ffdb546)
![w3](https://github.com/CharanBoga/weather-app/assets/117650577/aad50d01-0fb1-456f-825a-d1e18c0774db)




### How to Run:

1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run the `weather_app.py` script using Python.

### Contributing:

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or create a pull request.

