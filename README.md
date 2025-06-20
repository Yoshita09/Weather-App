# 🌤️ Weather App

A responsive and visually appealing weather forecast web app that allows users to search for the current weather and upcoming 5-day forecast of any city using the OpenWeatherMap API.

[🔗 Live Demo](https://yoshita09.github.io/Weather-App/)

---

## 📸 Preview

![Weather App Screenshot](assets/screenshot.png) <!-- Replace with an actual screenshot path -->

---

## 🚀 Features

- 🔍 Search for any city's weather
- 🌡️ Displays:
  - Current temperature
  - Weather condition
  - Wind speed
  - Humidity
  - Current date
- 📅 5-day forecast with icons and temperatures
- ⛅ Dynamic weather icons based on condition
- 📱 Mobile responsive layout

---

## 🛠️ Built With

- **HTML**
- **CSS**
- **JavaScript (Vanilla)**
- **OpenWeatherMap API**

---

## 🧠 How It Works

- User enters a city name and clicks search (or presses Enter)
- JavaScript fetches current weather and forecast data from OpenWeatherMap
- Weather data is displayed along with dynamic icons and formatted dates
- If city is not found, a 'Not Found' message is shown

---

## 📂 Project Structure
```
Weather-App/
│
├── assets/
│ ├── message/
│ │ ├── not-found.png
│ │ └── search-city.png
│ │
│ ├── weather/
│ │ ├── atmosphere.svg
│ │ ├── clear.svg
│ │ ├── clouds.svg
│ │ ├── drizzle.svg
│ │ ├── rain.svg
│ │ ├── snow.svg
│ │ └── thunderstorm.svg
│ │
│ └── bg.jpg
│
├── index.html
├── style.css
├── script.js
└── README.md # You're here!
```


---

## 🔑 API Key

The project uses the **OpenWeatherMap API**. The API key is currently hardcoded for demonstration, but it's **recommended to hide API keys** in production apps by using server-side code or environment variables.

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yoshita09/Weather-App.git

2. Navigate into the folder:
   `
cd Weather-App
```
3. Open index.html in your browser, or deploy using GitHub Pages.

---



