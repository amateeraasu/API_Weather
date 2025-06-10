# Weather API Script

This repository contains a simple Python script (`API_Weather.py`) that allows you to fetch current weather information using the OpenWeatherMap API.

## Features

* **Current Weather Data:** Retrieves current temperature and weather description for a specified location.
* **User Input:** Prompts the user to enter the city, state code, and country code for the desired weather forecast.
* **Error Handling:** Provides informative messages for successful requests or API errors.

## Getting Started

### Prerequisites

Before running the script, you'll need the following:

* Python 3.x installed.
* `requests` library: You can install it using pip:
    ```bash
    pip install requests
    ```
* An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation and Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Weather-API-Script.git](https://github.com/YourUsername/Weather-API-Script.git)
    cd Weather-API-Script
    ```

2.  **Obtain an API Key:**
    * Go to the [OpenWeatherMap website](https://openweathermap.org/api) and sign up for a free account.
    * Generate an API key from your account dashboard.

3.  **Update the API Key in the script:**
    * Open `API_Weather.py` in a text editor.
    * Replace `"---"` with your actual OpenWeatherMap API key:
        ```python
        api_key = "YOUR_API_KEY_HERE"
        ```

4.  **Run the script:**
    ```bash
    python API_Weather.py
    ```

5.  **Follow the prompts:**
    The script will ask you to enter the city, country code, and state code.

    ```
    Enter a city : London
    Enter a Country Code : UK
    Enter a State Code : 
    Weather in London: broken clouds, 15.6C
    ```
    *(Note: State code might not be applicable or necessary for all countries/cities. If unsure, you can leave it blank for some locations.)*

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).
