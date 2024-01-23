# Simple Weather App

## Overview

This is a simple Vue.js project that fetches weather information for a specified city using the OpenWeatherMap API. It displays the temperature, city name, today's date, and weather conditions such as rain, clouds, etc. Additionally, the background image changes based on the temperature – warm for temperatures above 16°C and cold for temperatures below.

## Screenshots

![cold weather](https://github.com/AnnaKabatova/vue-weather-app/assets/80786573/0db0661c-969d-4e52-a8c1-b60b713501a0)
![warm weather](https://github.com/AnnaKabatova/vue-weather-app/assets/80786573/bf0c59e7-3b62-46d4-88bc-4827f736a8c5)

## Getting Started

### Prerequisites

- Node.js installed
- OpenWeatherMap API key (Register at [openweathermap.org](https://openweathermap.org/) to obtain one, it's free)

### Installation

```bash
# Clone the repository
git clone https://github.com/AnnaKabatova/vue-weather-app.git

# Navigate to the project folder
cd vue-weather-app/vue-weather

# Install dependencies
npm install

## Configuration

- Open the `src/App.vue` file.
- Locate the variable `api_key` and replace `"YOUR_API_KEY"` with your OpenWeatherMap API key that you may find at https://home.openweathermap.org/api_keys page

## Run the App
npm run serve

Open your browser and navigate to http://localhost:8080 to view the app.
