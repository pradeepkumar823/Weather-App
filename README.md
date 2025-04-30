# 🌦️ React Weather App by PK

A clean and interactive weather application built with **React** and **Material UI**, powered by the **OpenWeatherMap API**. Users can search for any city to get real-time weather details in a stylish card layout.

![Weather App Screenshot](https://media.istockphoto.com/id/1332108668/photo/heatwave-with-warm-thermometer-and-fire-global-warming-and-extreme-climate-environment.jpg?s=1024x1024&w=is&k=20&c=QhEOtUgcu5E94FWjghUGyMZMUSF3DckCOvL7OqfgAVE=)

---

## 🚀 Features

- 🌍 Search weather by city name
- ☁️ Live weather data from OpenWeatherMap API
- 🌡️ Displays temperature, humidity, min/max temperature, feels-like temperature
- 🖼️ Dynamic image and icon updates based on weather
- 🎨 Material UI components with custom styling

---

## 🛠️ Tech Stack

- **React**
- **Material UI**
- **OpenWeatherMap API**
- **CSS**
- **React Hooks** (`useState`)

---

## 🌐 API Integration

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch live weather data.

### API Endpoint:
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}&units=metric

> ⚠️ **Note:** Replace the API key in `SearchBox.js` with your own OpenWeatherMap API key.

---

## 📁 Project Structure

weather-app/ ├── src/ │ ├── App.js │ ├── WeatherApp.js │ ├── SearchBox.js │ ├── InfoBox.js │ ├── SearchBox.css │ ├── InfoBox.css ├── public/ ├── package.json └── README.md



---

## 🧑‍💻 Getting Started

## 1. Clone the Repository

## bash
git clone [https://github.com/your-username/weather-app.git](https://github.com/pradeepkumar823/Weather-App.git)
cd weather-app
---
## Install Dependencies
npm install

---  

 
## Start the App
npm start
The app will run locally at http://localhost:3000.

---

## REACT_APP_API_KEY=your_api_key_here
## const API_KEY = process.env.REACT_APP_API_KEY;













