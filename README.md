

---

# ☀️ Sunstorm Weather Forecasting App

Sunstorm is a **Tkinter-based weather forecasting desktop application** built using **Python**. It allows users to select a country, state, and city from dropdowns and fetch **real-time weather data** using the **OpenWeatherMap API**.

---

## 📌 Features

* 🌍 **Country → State → City cascading dropdowns**
* ☁️ **Real-time weather info** using OpenWeatherMap API
* 🌡️ Displays:

  * Climate
  * Weather Description
  * Temperature (current, min, max)
  * Pressure
* 🎨 GUI designed using **Tkinter**
* 🛠️ Robust error handling and clear status messages

---

## 📸 GUI Preview

> ![Sunstorm App Screenshot](#)

---

## 🚀 How to Run

### 1. **Clone this Repository**

```bash
git clone https://github.com/Sonali8412/sunstorm-weather-app.git
cd sunstorm-weather-app
```

### 2. **Install Required Library**

This project uses the `requests` library:

```bash
pip install requests
```

### 3. **Get OpenWeatherMap API Key**

* Go to [https://openweathermap.org/api](https://openweathermap.org/api)
* Sign up and generate a free API key.
* Replace the API key in the code:

```python
api_key = "your_api_key_here"
```

### 4. **Run the App**

```bash
python sunstorm_weather_app.py
```

---

## 🧠 How It Works

* The app uses a nested Python dictionary (`country_data`) to store all supported countries, states, and cities.
* On selecting a country, available states update automatically.
* On selecting a state, relevant cities appear.
* The `Fetch Weather` button uses the selected city name to call the **OpenWeatherMap API**, retrieves weather data, and displays it.

---

## 🛡️ Error Handling

* ✅ City not selected → prompts user to choose one.
* ❌ Invalid city name or API error → “City not found” message.
* 🛜 Handles connection issues gracefully.

---

## 🛠️ Built With

* [Python](https://www.python.org/)
* [Tkinter](https://docs.python.org/3/library/tkinter.html) — GUI library
* [OpenWeatherMap API](https://openweathermap.org/)

---

## 📁 File Structure

```
sunstorm-weather-app/
│
├── sunstorm_weather_app.py     # Main Python file
└── README.md                   # Project documentation
```

---

## 📌 Future Enhancements

* 🌐 Add search functionality instead of dropdowns
* 📍 Detect user location via IP
* 📊 Add weather icons and graphs

---

## 🤝 Acknowledgments

* Thanks to [OpenWeatherMap](https://openweathermap.org/) for their free weather API.

---

## 🧑‍💻 Author


> [GitHub Profile](https://github.com/Sonali8412)

---
