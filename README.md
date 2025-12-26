# React Weather Forecast App

A simple and responsive weather forecasting application built with React and Vite that allows users to search for a city and view real-time weather information.

---

## Description

The React Weather Forecast App is a frontend project designed to demonstrate practical React skills such as component-based architecture, state management, API integration, and conditional rendering. The application fetches live weather data from a public weather API and displays current weather conditions in a clean and user-friendly interface.

This project is intended for learning purposes and as a portfolio project.

---

## Features

- Search weather by city name
- Display current temperature and weather condition
- Shows humidity and wind speed
- Handles loading and error states
- Responsive layout for different screen sizes

---
## How the Application Works

1. The user enters a city name in the search input.
2. The application sends a request to the weather API using the city name.
3. The API returns real-time weather data.
4. The application updates the UI with the retrieved data.
5. If the request fails, an appropriate error message is displayed.

---

## Data Displayed

For each searched city, the following information is shown:

- City name
- Current temperature (°C)
- Weather description
- Humidity percentage
- Wind speed

---
## Technologies Used

- React
- Vite
- JavaScript (ES6+)
- CSS
- OpenWeatherMap API
- Git & GitHub

---

## Screenshots

<img width="1844" height="940" alt="Screenshot1" src="https://github.com/user-attachments/assets/e748e5f3-613b-4a6d-90e4-665b40cc57e7" />
---
## Installation and Setup

Follow the steps below to run the project. 
1. Clone the repository
   ```bash
   git clone https://github.com/Mercurelab-com/react-weather-app.git
2. Navigate to the project directory
   ```bash
   cd react-weather-app
3. Install dependencies
   ```bash
   npm install
4. Configure environment variables
   - Create a .env file in the root directory and add your API key:
     ```env
     VITE_APP_iD=your_api_key_here
  - The .env file is ignored by Git to protect sensitive information
5. Run the development server
     ```bash
         npm run dev
- The application will be available at the local URL shown in the terminal 

----
## Error Handling
Displays a message when a city is not found
Handles network or API errors gracefully
Prevents empty search submissions
----
## Limitations
Only current weather data is supported
Forecast data is not yet implemented
Requires an active internet connection
---
## Future Improvements
5-day weather forecast
Location-based weather using geolocation
Temperature unit toggle (°C / °F)
Dark mode
Improved UI and animations
---

## Learning Objectives
This project was built to:
 - Practice React component design
 - Understand API consumption in frontend application
 - Manage state and side effects using React hooks
 - Improve Git and GitHub workflow
 - Build a clean, documented portfolio project
---

## Author 
- Zed Mercure N. N.
- Computer Engineering Graduate
