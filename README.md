# weather-data-tracker
fetch+save+plot the data of openweather web 

🌦️ Weather Data Tracker

A simple Python project that tracks and visualizes live (or simulated) weather data for multiple cities — all built using only a mobile device 💪

🚀 What I Learned

This project helped me understand how to:

Use the OpenWeather API to fetch real-time weather data 🌍

Handle API keys securely using getpass and environment variables

Create a simulation mode to generate random weather data when no API key is available

Store weather data in CSV and Excel files using pandas 📊

Visualize temperature and humidity trends with matplotlib 📈

Manage time zones using pytz and timestamps for each reading

🧠 Project Flow

1. Enter or skip the API key (simulation mode activates automatically if skipped)


2. Fetch or simulate data for multiple cities (Hyderabad, Kerala, Mumbai, etc.)


3. Store the data with timestamps into CSV and Excel files


4. Compare new readings with previous data


5. Visualize the last few readings for each city in line charts


🧰 Technologies Used

Python 🐍

Requests (for API calls)

Pandas (for data storage and comparison)

Matplotlib (for visualization)

pytz and datetime (for time handling)

📸 Output Preview

Real-time or simulated data printed in the console

Saved files:

weather_data.csv

weather_data.xlsx


Graphs showing temperature and humidity changes for each city

⚙️ How It Works

If you enter a valid API key → Fetches real weather data

If you skip or the request fails → Generates random realistic data

Every time you run the code, new data is added (not replaced)

You’ll get temperature and humidity plots for each city

💡 Example Use Case

You can use this script to track how the weather changes daily or simulate data for practice if you don’t have an API key.

🪄 Future Improvements

Add more cities dynamically

Schedule automatic weather tracking

Send daily weather summaries via email or WhatsApp

🧍‍♂️ About Me

I’m a student learning Python step by step — building projects fully on mobile using Google Colab 📱
This is my second project after my Book Price Tracker, and I’m loving the progress 🔥

⭐ If you like this project, consider giving it a star on GitHub!
