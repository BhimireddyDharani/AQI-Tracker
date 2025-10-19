# 🌍 AQI Tracker – Real-Time Air Quality Monitoring and Alerts

## 📘 Project Overview
**AQI Tracker** is a real-time air quality monitoring and alert system that collects live pollution data using the **OpenWeatherMap API**, computes the **Air Quality Index (AQI)**, detects pollution spikes, and visualizes the results on an interactive dashboard.  

This project aims to empower citizens, students, and environmental authorities with real-time insights to monitor air quality, understand pollution trends, and take immediate action.

---

## 🎯 Objectives
- Continuously monitor real-time air pollution data for any city.  
- Calculate AQI dynamically based on multiple pollutant readings.  
- Detect sudden pollution spikes and generate alerts automatically.  
- Display interactive visualizations and city-based comparisons.  
- Build a modular, scalable data engineering pipeline.

---

## ⚙️ Data Engineering Lifecycle

| Stage | Description |
|--------|-------------|
| **Data Ingestion** | Fetches real-time air quality data from OpenWeatherMap API. |
| **Data Storage** | Stores raw and processed data locally in CSV format. |
| **Data Transformation** | Cleans data, computes AQI, and detects pollution spikes. |
| **Data Visualization** | Displays processed results using Streamlit dashboard. |
| **Data Collection** | Aggregates data from multiple cities for historical analysis. |

---

## 🧠 Features
- 🌐 Real-time air quality data collection from OpenWeatherMap API.  
- 🧮 AQI computation using standard air pollutant concentration levels.  
- 🚨 Automatic pollution spike detection and alert generation.  
- 📊 Interactive **Streamlit** dashboard for visualization.  
- 🗂️ Data export in CSV format for analysis and reporting.  
- 📈 Multi-city monitoring and trend comparison.  
- ⚙️ Extendable architecture for IoT and ML integration.

---

## 🏗️ Project Structure
AQI_Tracker/

- ingestion.py # Fetches live data from OpenWeatherMap API
- storage.py # Manages saving and accessing CSV files
- transform.py # Cleans and transforms data, computes AQI
- visualize.py # Creates charts and Streamlit plots
- collection.py # Handles multi-city data collection
- main.py # Integrates all pipeline stages
- dashboard.py # Streamlit dashboard for data visualization
- templates/ # HTML templates for Flask interface
- static/ # CSS, images, and styling
- config.py # Configuration file with API key
- requirements.txt # Dependencies list
## 🧰 Technologies Used
- **Language:** Python  
- **Frameworks:** Flask, Streamlit  
- **API:** OpenWeatherMap Air Pollution API  
- **Libraries:** Pandas, Matplotlib, Plotly, Requests, JSON, Time  
- **Storage:** Local CSV files  
- **Tools:** Visual Studio Code, GitHub  

---

⚙️ Installation Guide

Step 1️⃣ — Clone the Repository

git clone https://github.com/<your-username>/AQI_Tracker.git
cd AQI_Tracker


Step 2️⃣ — Install Required Packages

pip install -r requirements.txt


Step 3️⃣ — Configure API Key
Open the config.py file and add your OpenWeather API Key:

API_KEY = "your_openweather_api_key_here"


Step 4️⃣ — Run the Application
Run the backend Flask server:

python main.py


Then launch the visualization dashboard:

streamlit run dashboard.py


##🚀 How to Run the Project
streamlit run dashboard.py
## 📤 Outputs
🧾 Processed Data Output

📊 Dashboard Output
<img width="1600" height="583" alt="image" src="https://github.com/user-attachments/assets/497781e9-bca0-4b54-bcc0-281075ac9a10" />
<img width="1600" height="668" alt="image" src="https://github.com/user-attachments/assets/7686e44d-bb36-4aed-9ce0-84299d4ee601" />


