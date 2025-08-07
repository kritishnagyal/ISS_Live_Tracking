# ISS_Live_Tracking

**Author:** Kritish Nagyal  
**Program:** B.Tech in Electronics and Communication (Avionics)  
**Project Type:** Astronomy, Python Programming, Satellite Tracking  
**Dashboard Link:** [Live ISS Tracker Dashboard](http://192.168.29.68:8501)  
**GitHub:** [kritishnagyal](https://github.com/kritishnagyal)

---

## 🌍 Project Overview

This project demonstrates how Python can be used to **track the International Space Station (ISS)** in real time. It includes geospatial analysis, orbital predictions, and visualization tools. The final result is an interactive dashboard using **Streamlit** and **Folium** that shows the ISS’s real-time position, speed, altitude, and next visible passes over any location.

### 🔭 What You'll Learn

- Working with **live Two-Line Element (TLE)** data from CelesTrak
- Predicting **ISS pass times** for any location on Earth
- Plotting **ground tracks** and orbital paths using **Skyfield** and **Cartopy**
- Creating a **dashboard UI** using **Streamlit**
- Exporting ISS passes to CSV for multiple cities

---

## ⚙️ Installation & Environment Setup

### ✅ Prerequisites

- Python 3.8 or higher
- Internet connection to fetch live satellite data
- IDE like VS Code / Jupyter / PyCharm

### 🧪 Install Required Libraries

```bash
pip install requests skyfield numpy matplotlib ipywidgets pandas cartopy streamlit folium streamlit-folium
