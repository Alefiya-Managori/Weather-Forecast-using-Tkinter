# 🌤️ Weather App using Tkinter and OpenWeatherMap API

This is a Python desktop application built using **Tkinter**, **Geopy**, and the **OpenWeatherMap API**. It allows users to search for any city and view the current weather, temperature, humidity, pressure, wind speed, and local time.

---

## 🚀 Features

- 🕒 Displays local time using timezone data
- 🌡️ Current weather condition, temperature (°C), humidity, pressure
- 🌬️ Wind speed and weather description
- 🎨 Beautiful UI with search bar, icons, and images

---

## 🧰 Technologies Used

- Python 3.x
- Tkinter (GUI)
- Pillow (Image loading)
- Requests (API calls)
- Geopy (Get location coordinates)
- TimezoneFinder & pytz (Convert location to timezone)
- OpenWeatherMap API (Weather data)

---

## 🔑 How to Get the OpenWeatherMap API Key

1. Visit [https://home.openweathermap.org/users/sign_up](https://home.openweathermap.org/users/sign_up)
2. Create a free account.
3. Once logged in, go to [My API Keys](https://home.openweathermap.org/api_keys).
4. Copy your **API Key**.
5. In the script, paste your key like this:

   ```python
   api = f"https://api.openweathermap.org/data/2.5/weather?q={city}&appid=YOUR_API_KEY_HERE"
   
## 📦 Installation
Prerequisites:
Python 3.x installed

Required libraries:
pip install requests pytz geopy timezonefinder

Add the images:
Ensure the following image files are in the same folder as your script:
search.png
search_icon.png
logo.png
box.png

## ▶️ Running the App
Insert your OpenWeatherMap API key in the code.

Run the Python script:
python weather_app.py

📸 Screenshot


![Screenshot 2025-05-24 123549](https://github.com/user-attachments/assets/e93cc051-eb5d-46a7-920a-28ac20f618b1)
