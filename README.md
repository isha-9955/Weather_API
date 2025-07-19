# 🌦️ Weather & Forecast 

This is a simple Python application that provides real-time **current weather** and a **5-day forecast** (temperature and humidity) for any city using the **OpenWeatherMap API**. The forecast is visualized using `matplotlib`, and data is saved as a CSV file.

## 🧰 Features

- 🌍 Real-time current weather report (Temperature, Humidity, Weather Description with Emoji).
- 📊 Temperature forecast plot (5 days).
- 💧 Humidity forecast plot (5 days).
- 📁 Automatically saves forecast data as a CSV file.
- ❌ Graceful error handling for incorrect city names or network issues.

## 🔧 Requirements

Make sure you have Python 3.6+ and install the following packages:

```bash
pip install requests matplotlib pandas seaborn
```

## 🚀 How to Run

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Replace your API key in the code:

```python
API_KEY = "your_api_key_here"
```

3. Run the app:

```bash
python weather_app.py
```

4. Enter your city when prompted and view the output and graphs.

## 📦 Output

- Console output showing:
  - City name
  - Current temperature and humidity
  - Weather description with an emoji
- Two plots:
  - 📈 Temperature Forecast (5 Days)
  - 💧 Humidity Forecast (5 Days)
- A CSV file named `<city>_5_day_forecast.csv`

## 🧑‍💻 Built With

- [Python](https://www.python.org/)
- [OpenWeatherMap API](https://openweathermap.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)

## 👩‍💻 Author

**Isha Zope**

---

🔗 GitHub: https://github.com/isha-9955
