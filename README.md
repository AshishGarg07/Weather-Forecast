# Weather Forecast Application

A weather forecasting application built with Python using the OpenWeatherMap API and the `customtkinter` library. This GUI-based app allows users to search for a city and view current weather conditions, including temperature, humidity, wind speed, and more.

## Features

- Search weather by city name
- Displays temperature, feels like, pressure, humidity, wind speed, sunrise, and sunset times
- Shows country information and a weather condition icon (e.g., clear, cloudy, rain, etc.)
- User-friendly graphical interface with real-time data

## Technologies Used

- **Python**
- **customtkinter** - For creating the GUI
- **OpenWeatherMap API** - To fetch live weather data
- **Pillow (PIL)** - For handling image files
- **requests** - To send HTTP requests to the OpenWeatherMap API

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/YashGarg1122/WeatherForecast.git
    ```

2. Install the required dependencies:

    ```bash
    pip install customtkinter Pillow requests
    ```

3. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) by creating an account.

4. Update the `api_key` in the Python script with your OpenWeatherMap API key:

    ```python
    api_key = "your_api_key"
    ```

5. Run the application:

    ```bash
    python weather_forecast.py
    ```

## Usage

- Enter the city name and hit the "Search" button or press Enter.
- The weather information for the entered city will be displayed on the GUI, including temperature, feels like temperature, pressure, humidity, wind speed, sunrise, and sunset times.


## License

This project is licensed under the GPL 3 License.

---

Feel free to contribute to the project by opening issues or submitting pull requests!
