# weatherApp1
# WeatherApp README

## Introduction

The WeatherApp is a simple Java application that allows users to retrieve and display weather information for a specified location. This README provides an overview of the application's components and how to use it.

## Prerequisites

Before running the WeatherApp, ensure you have the following:

1. Java Development Kit (JDK) installed.
2. The required external libraries are included in the project.
3. An internet connection to fetch weather data from external APIs.

## Components

The WeatherApp consists of two main classes:

### 1. AppLauncher

- Main entry point of the application.
- Initiates the application's GUI by creating an instance of `WeatherAppGui`.
- Uses Swing to create the graphical user interface.

### 2. WeatherApp

- Contains methods to fetch weather data for a given location.
- Utilizes external APIs to retrieve weather and geolocation information.
- Provides methods to parse and extract relevant data from the APIs.
- Converts weather condition codes to more readable descriptions.
- Handles errors and exceptions in case of API request failures.

### 3. WeatherAppGui

- Represents the graphical user interface (GUI) of the WeatherApp.
- Allows users to input a location, retrieve weather information, and display it on the GUI.
- Displays weather data, including temperature, weather conditions, humidity, and windspeed.
- Supports searching for weather data for different locations.
- Displays weather condition icons based on the retrieved data.

## How to Use

1. Clone or download the WeatherApp project to your local machine.

2. Make sure you have the required libraries and dependencies.

3. Open the project in your preferred Java development environment (e.g., Eclipse, IntelliJ IDEA).

4. Run the `AppLauncher` class to start the WeatherApp.

5. The WeatherApp GUI will appear, allowing you to enter a location in the text field and click the search button to retrieve weather information.

6. The GUI will display the following weather information:
   - Weather condition icon.
   - Temperature in Celsius.
   - Weather condition description (e.g., Clear, Cloudy, Rain, Snow).
   - Humidity percentage.
   - Windspeed in kilometers per hour.

7. You can search for different locations and retrieve their weather data by entering a location name and clicking the search button.

## Dependencies

The WeatherApp uses the following external libraries:

- JSON-Simple: Used for parsing JSON data from the weather and geolocation APIs.
- Swing (Java GUI library): Used to create the graphical user interface.

## Troubleshooting

If you encounter any issues, please make sure you have an internet connection and that the required libraries are properly included in your project.

## Disclaimer

This WeatherApp is a simple demonstration project and may not include advanced error handling or production-level features. It is intended for educational purposes and can serve as a starting point for building more advanced weather applications.

For questions or feedback, contact the project maintainers.

## Credits

This WeatherApp was created by [Your Name].

## License

This WeatherApp is open-source and distributed under the [License Name] license. See the `LICENSE` file for details.
