# 🌤️ Weather Info CLI App

A simple Python-based CLI application that fetches and displays real-time weather data for any city using the **OpenWeatherMap API**.

---

## 🧰 Features

- 🌍 Input any city name and get current weather conditions
- 🌡️ Displays temperature (in Kelvin) and a short weather description
- 🔌 Uses OpenWeatherMap REST API for real-time data
- ⚙️ Error handling for invalid inputs or failed API requests

---

## 🖥️ How It Works

1. Takes a city name as input from the user
2. Sends a `GET` request to the OpenWeatherMap API
3. Parses the JSON response to extract:
   - Current temperature
   - Weather description
4. Displays the data in the terminal

---

## 📦 Requirements

- Python 3.x
- `requests` library

Install dependencies (if not already installed):

```bash
pip install requests
