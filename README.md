# synent-task6-weatherapp-chooenyi
Real-time CLI/Web Weather App using Python and OpenWeatherMap API
# Task 6: Real-Time Weather App (API Integration)

A command-line Python application built for the **Synent Technologies Python Development Internship Program**. It fetches and displays real-time weather conditions for any city worldwide using the OpenWeatherMap REST API.

## Features
- **Real-Time Weather Data:** Displays condition description, current temperature, "feels like" temperature, min/max range, humidity, atmospheric pressure, wind speed, and local sunrise/sunset times.
- **Robust Error Handling:** Gracefully handles invalid/misspelled city names (`HTTP 404`), invalid API keys (`HTTP 401`), empty inputs, and network timeouts.
- **Secure Secret Management:** Loads the API key via environment variables (`python-dotenv`) rather than hardcoding credentials.

## Tech Stack
- Python 3
- `requests`
- `python-dotenv`
- OpenWeatherMap Current Weather API (`/data/2.5/weather`)

## Setup & Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-github-username>/synent-task6-weatherapp-chooenyi.git
   cd synent-task6-weatherapp-chooenyi
