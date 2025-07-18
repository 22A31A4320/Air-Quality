# Air-Quality
🌍 A simple Streamlit app to detect air pollution levels by fetching real-time data from OpenWeatherMap API using latitude and longitude inputs.

# 🌍 Air Quality Detector

A simple and beginner-friendly Streamlit web app to detect air quality by fetching real-time air pollution data using the OpenWeatherMap API. Enter your location’s **latitude** and **longitude** to see key pollutant levels instantly.

---

## 📌 What It Does

- 🔍 Takes latitude and longitude inputs from the user.
- ⚡ Sends a request to the OpenWeatherMap **Air Pollution API**.
- 📄 Parses the JSON response and extracts pollutant component values.
- ✅ Displays all major air quality components, including:
  - CO (Carbon Monoxide)
  - NO₂ (Nitrogen Dioxide)
  - O₃ (Ozone)
  - SO₂ (Sulfur Dioxide)
  - PM2.5
  - PM10
  - NH₃ (Ammonia)

---

## ⚙️ How to Run

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/22A31A4320/Air-Quality.git
cd Air-Quality
2️⃣ Install Dependencies

bash
Copy
Edit
pip install streamlit requests
3️⃣ Add Your API Key
Open air_quality_detector.py and replace the apikey variable with your own OpenWeatherMap API key.

4️⃣ Run the App

bash
Copy
Edit
streamlit run air_quality_detector.py
5️⃣ Use the App

Enter your latitude and longitude.

Click Submit to view the real-time air pollutant component values.

📂 Project Structure
bash
Copy
Edit
Air-Quality/
 ├── air_quality_detector.py   # Main Streamlit app script
 ├── requirements.txt          # Project dependencies
 ├── LICENSE                   # MIT License
 ├── .gitignore                # Python ignore rules
 ├── README.md                 # Project overview & instructions
⚡ Tech Stack
Python

Streamlit — for the web interface

Requests — for HTTP API calls

OpenWeatherMap API — for real-time air quality data

✅ Example Output
bash
Copy
Edit
{'co': 220.5, 'no': 0.02, 'no2': 33.7, 'o3': 66.5, 'so2': 5.8, 'pm2_5': 95.2, 'pm10': 150.3, 'nh3': 12.1}
These numbers show the real-time pollutant concentrations for your chosen coordinates.

🚀 Future Improvements
This is a simple base project you can expand by:

Adding city name input and geocoding.

Showing AQI levels with health category labels.

Visualizing data with charts or gauges.

Adding maps to locate the coordinates visually.

Deploying the app on Streamlit Community Cloud or other hosting.
