Weather App 🌤️

A simple and elegant Python Weather Application built using PyQt5 that fetches real-time weather data from the OpenWeatherMap API. Users can enter any city name to view the current temperature, weather description, and an emoji representation of the weather condition.

🚀 Features

🔍 Search weather by city name

🌡️ Displays real-time temperature in Celsius

🌥️ Shows weather condition with appropriate emoji

🎨 Clean and modern PyQt5 user interface

⚠️ Robust error handling for:

Invalid city names

API errors (400, 401, 403, 404, 500, etc.)

Network/connection issues

Timeout and redirect issues

🛠️ Tech Stack

Python

PyQt5

OpenWeatherMap API

Requests Library

📦 Installation

Clone the repository:

git clone https://github.com/your-username/weather-app.git
cd weather-app


Install required dependencies:

pip install PyQt5 requests


Add your OpenWeatherMap API key in the script:

api_key = "YOUR_API_KEY"

▶️ How to Run

Run the Python script:

python weather_api_app.py


The Weather App window will open, allowing you to enter a city and get instant weather details.

📁 Project Structure
📂 Weather-App
│── weather_api_app.py
│── Weather-icon.png
│── README.md
