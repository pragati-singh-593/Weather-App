#  Weather App

A responsive, web-based Weather Application built using **HTML, CSS, and JavaScript** that provides real-time weather information for cities around the world.

The application integrates with the **OpenWeatherMap API** to fetch and display current weather conditions, including temperature, humidity, wind speed, and atmospheric pressure. It also features dynamic backgrounds that change according to the current weather conditions, creating a more interactive user experience.

##  Live Demo

**(https://weather-app-ps593.netlify.app/)**

##  Features

- **City-Based Weather Search:** Search for weather information by entering a city name.
- **Real-Time Weather Data:** Fetches current weather information using the OpenWeatherMap API.
- **Temperature Details:** Displays current, minimum, and maximum temperatures in Celsius.
- **Weather Conditions:** Shows the current weather status with corresponding weather icons.
- **Additional Weather Information:** Displays feels-like temperature, humidity, atmospheric pressure, and wind speed.
- **Dynamic Backgrounds:** Background images automatically change according to weather conditions such as clear skies, clouds, rain, snow, and thunderstorms.
- **Date and Time:** Displays the current date and the time at which the weather information was retrieved.
- **Input Validation:** Provides alerts for empty searches and invalid city names.
- **Responsive Design:** Adapts the application layout for different screen sizes, including mobile devices.

##  Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structuring the application |
| CSS3 | Styling, layouts, and responsive design |
| JavaScript (ES6) | Application logic and DOM manipulation |
| OpenWeatherMap API | Fetching real-time weather information |
| Font Awesome 5 | Weather icons |
| SweetAlert | Interactive alerts and error messages |
| Google Fonts | Typography |

##  Project Structure

```text
Weather-App/
│
├── img/
│   ├── bg.jpg
│   ├── clouds.jpg
│   ├── rainy.jpg
│   ├── clear.jpg
│   ├── snow.jpg
│   ├── sunny.jpg
│   ├── drizzle.jpg
│   ├── mist.jpg
│   └── ...
│
├── index.html
├── style.css
├── script.js
└── README.md
```

##  Getting Started

Follow these steps to run the project locally.

### Prerequisites

- A modern web browser.
- A code editor such as Visual Studio Code.
- An OpenWeatherMap API key.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/pragati-singh-593/Weather-App.git
```

**2. Navigate to the project directory**

```bash
cd Weather-App
```

**3. Configure the API key**

- Create an account on [OpenWeatherMap](https://openweathermap.org/api).
- Generate an API key.
- Open `script.js` and replace the API key placeholder in the `weatherApi` configuration with your own key.

**4. Run the application**

Open the project in Visual Studio Code and launch `index.html` using the Live Server extension.

Alternatively, open `index.html` directly in a supported browser.

##  How It Works

1. The user enters a city name in the search field.
2. JavaScript captures the input when the Enter key is pressed.
3. The application sends a request to the OpenWeatherMap Current Weather API.
4. The API returns weather information in JSON format.
5. JavaScript processes the response and dynamically updates the DOM.
6. Weather details, including temperature, humidity, pressure, and wind speed, are displayed.
7. The background image and weather icon are updated according to the retrieved weather conditions.

##  Future Improvements

- Add support for weather forecasts for upcoming days.
- Implement temperature unit conversion (Celsius/Fahrenheit).
- Introduce automatic weather detection using device location.
- Improve API error handling and loading indicators.
- Enhance the user interface with additional weather visualizations.

##  Author

**Pragati Singh**

- GitHub: [@pragati-singh-593](https://github.com/pragati-singh-593)
- Project Repository: [Weather-App](https://github.com/pragati-singh-593/Weather-App)

---

 If you find this project interesting, feel free to explore the repository!
