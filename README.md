# API_Weather

This repository contains a Jupyter Notebook (`API_Weather.ipynb`) that allows you to fetch current weather information using the OpenWeatherMap API.

## Features

* **Current Weather Data:** Retrieves current temperature and weather description for a specified location.
* **Interactive Input:** Utilizes Jupyter's interactive capabilities to prompt the user for city, state code, and country code.
* **Error Handling:** Provides informative messages for successful requests or API errors.

## Getting Started

### Prerequisites

Before running the notebook, you'll need the following:

* Python 3.x installed.
* Jupyter Notebook installed. You can install it using pip:
    ```bash
    pip install notebook
    ```
* `requests` library: You can install it using pip:
    ```bash
    pip install requests
    ```
* An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation and Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/API_Weather.git](https://github.com/YourUsername/API_Weather.git)
    cd API_Weather
    ```

2.  **Obtain an API Key:**
    * Go to the [OpenWeatherMap website](https://openweathermap.openweathermap.org/api) and sign up for a free account.
    * Generate an API key from your account dashboard.

3.  **Set your OpenWeatherMap API Key as an Environment Variable (Recommended for Security):**
    For security, it's recommended to store your API key as an environment variable named `OPENWEATHER_API_KEY`. The notebook will then read this variable.

    * **On Linux/macOS:**
        Open your terminal and run:
        ```bash
        export OPENWEATHER_API_KEY="YOUR_API_KEY_HERE"
        ```
        (To make this persistent across sessions, add this line to your `~/.bashrc`, `~/.zshrc`, or equivalent shell configuration file.)

    * **On Windows (Command Prompt):**
        Open Command Prompt and run:
        ```cmd
        set OPENWEATHER_API_KEY="YOUR_API_KEY_HERE"
        ```
        (This sets the variable temporarily for the current session. For a permanent setting, search for "Environment Variables" in Windows and add a new system or user variable.)

    * **On Windows (PowerShell):**
        Open PowerShell and run:
        ```powershell
        $env:OPENWEATHER_API_KEY="YOUR_API_KEY_HERE"
        ```
        (This is temporary. For permanent setting, you can add it to your PowerShell profile.)

4.  **Launch Jupyter Notebook:**
    From the `API_Weather` directory, run:
    ```bash
    jupyter notebook
    ```

5.  **Open and Run the Notebook:**
    * In your web browser, Jupyter will open. Click on `API_Weather.ipynb` to open the notebook.
    * Go through the cells and run them in order. The notebook will prompt you for the city, country code, and state code.

    Expected output in the notebook might look like:
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
