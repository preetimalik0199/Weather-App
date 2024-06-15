# Dynamic Weather App

A feature-rich weather application developed using HTML, CSS, and JavaScript. This app provides real-time weather information with a dynamic user interface that adapts to the current weather conditions.

## Features

- **Dynamic Weather Data:** Provides real-time temperature, minimum and maximum temperatures, and more.
- **Dynamic Background Images:** Changes the background image based on the weather status.
- **Dynamic Weather Icons:** Displays weather icons that change according to the current weather status.
- **Comprehensive Weather Information:** Offers detailed data such as feels-like temperature, humidity, pressure, and wind speed.
- **Input Validation:** Does not accept empty inputs.
- **Error Handling:** Alerts the user if the entered city name does not match any data from the API.
- **Good UX/UI:** Ensures a user-friendly and visually appealing interface.

## Demo

(Include a screenshot or a link to a live demo if available)

## Getting Started

### Prerequisites

No special software is required to run this project. You only need a modern web browser and an internet connection.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-app
    ```

3. Open the `index.html` file in your web browser:

    ```bash
    open index.html
    ```

### API Key

This project uses a weather API to fetch data. You need to obtain an API key from a weather service provider (e.g., OpenWeatherMap).

1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Obtain your API key from the API keys section.
3. Add your API key to the `script.js` file:

    ```javascript
    const apiKey = 'YOUR_API_KEY';
    ```

## Usage

1. **Enter a City Name:**
   - Type the name of the city in the input field and click the "Get Weather" button.

2. **View Weather Data:**
   - The app will display the current weather data, including temperature, humidity, pressure, and wind speed.
   - The background image and weather icon will dynamically change based on the weather status.

3. **Error Handling:**
   - If the input field is empty, the app will not proceed and will prompt you to enter a city name.
   - If the city name does not match any data from the API, the app will alert you with an error message.

## Project Structure


weather-app/
├── index.html      # The main HTML file
├── style.css       # The CSS file for styling
└── script.js       # The JavaScript file containing the logic for fetching and displaying weather data


## Code Overview

### HTML (`index.html`)

- Basic structure of the webpage
- Contains input field and buttons for fetching weather data

### CSS (`style.css`)

- Styles the appearance of the weather app
- Provides responsive design and dynamic background images

### JavaScript (`script.js`)

- Fetches weather data from the API
- Handles the dynamic display of weather data, background images, and icons
- Implements input validation and error handling
