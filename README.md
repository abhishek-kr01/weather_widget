# Weather Widget

## Overview

**Weather Widget** is a sleek, user-friendly weather application built with React and Material-UI. It allows users to search for any city and view real-time weather details, including temperature, humidity, and weather conditions. The app dynamically updates the UI with relevant weather icons and background images based on the weather status.

## Features

- **Search for any city** to get real-time weather updates.
- **Dynamic UI**: Changes background based on weather conditions.
- **Displays temperature, humidity, and weather conditions.**
- **Error handling** for incorrect city names.
- **Responsive design** with Material-UI components.

## Tech Stack

- **Frontend:** React.js, JavaScript, Material-UI
- **State Management:** React Hooks (useState)
- **API:** OpenWeatherMap API
- **Styling:** CSS Modules, Material-UI
- **Build Tool:** Vite

## Folder Structure

```
Weather_Widget/
│── node_modules/          # Dependencies
│── public/                # Static assets
│── src/
│   ├── assets/            # Images & assets
│   ├── components/        # React components
│   │   ├── InfoBox.jsx    # Displays weather info
│   │   ├── SearchBox.jsx  # Search input for city
│   │   ├── WeatherApp.jsx # Main app component
│   ├── styles/            # CSS files
│   │   ├── InfoBox.css
│   │   ├── SearchBox.css
│   │   ├── App.css
│   ├── index.js           # Entry point
│   ├── main.jsx           # Main React file
│── .env                   # Environment variables
│── .gitignore             # Git ignore file
│── package.json           # Dependencies
│── vite.config.js         # Vite config file
│── README.md              # Project documentation
```

## Installation & Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/abhishek-kr01/weather_widget
   cd weather-widget
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Set up API Key:**
   - Create a `.env` file in the root directory and add:
     ```sh
     VITE_WEATHER_API_KEY=your_api_key_here
     ```
4. **Start the development server:**
   ```sh
   npm run dev
   ```

## How to Use

1. Enter a **city name** in the search bar.
2. Click **Search** to fetch live weather data.
3. View **temperature, humidity, and weather conditions**.
4. The background **changes dynamically** based on the weather.

## API Reference

- [OpenWeatherMap API](https://openweathermap.org/api)

## Author

Developed by **Abhishek Kumar**. Connect with me on [GitHub](https://github.com/abhishek-kr01).
