# Weather & AQI-Based Patient Alert System

This Python project fetches real-time **weather** and **air quality data** to alert patients with **chronic respiratory conditions** (like asthma and COPD) when environmental conditions may be risky for their health.

It combines data from:
- **NOAA National Weather Service (NWS)** for hourly weather forecasts
- **AirNow API** for daily AQI data

The system:
- Checks individual patient thresholds for temperature and AQI
- Generates condition-specific alerts
- Sends alerts via **email** (optional)
- Outputs the alerts in a clean CSV table

---

## 🚀 Features

- Real-time hourly temperature and daily AQI retrieval
- Intelligent alert logic based on condition-specific thresholds
- Custom patient table (you can modify/add patients)
- Email notifications using Gmail SMTP (or leave blank to skip)
- Saves outputs as CSV for reporting
