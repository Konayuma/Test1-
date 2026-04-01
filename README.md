# Weather Trend Planner

## Project Overview
[cite_start]The Weather Trend Planner is a lightweight web application designed to help users analyze upcoming weather trends for a specific city and determine the best day for outdoor activities[cite: 3]. [cite_start]The application retrieves weather forecast data from a weather API, visualizes temperature trends using a line chart, and generates useful insights from the forecast data[cite: 4].

## Features
* [cite_start]**City Search:** Users can enter a city name to fetch and view the weather forecast[cite: 12, 88].
* [cite_start]**Current Weather:** Displays the city name, current temperature, and weather condition[cite: 22, 23, 24, 25, 90].
* [cite_start]**Temperature Trend Chart:** Features a line chart displaying temperature trends over the next 5-7 days[cite: 31, 91].
* [cite_start]**Activity Recommendations:** Suggests the best day for outdoor activities based on forecast data[cite: 93, 94].
* [cite_start]**Weather Warnings:** Generates insights and alerts users about extreme weather conditions, such as heat warnings for temperatures over 35°C and cold warnings for temperatures under 5°C[cite: 48, 49, 95, 96].

## Tech Stack
* [cite_start]**Frontend:** React [cite: 99]
* [cite_start]**Charting:** Chart.js [cite: 100] (via `react-chartjs-2`)
* [cite_start]**Styling:** CSS [cite: 101]

## API Integration
[cite_start]This project integrates with the **OpenWeather API** to fetch forecast data[cite: 7]. [cite_start]The raw data, which is provided in 3-hour intervals, is processed and transformed within the application into daily averages for the chart visualization[cite: 67].

## Getting Started

### Prerequisites
* Node.js and npm installed on your machine.
* An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd weather-trend-planner
