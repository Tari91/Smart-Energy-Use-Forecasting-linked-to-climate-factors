# 🧠 Smart Energy Use Forecasting Linked to Climate Factors

## 📘 Overview
This project demonstrates a **machine learning–based approach** for forecasting smart energy usage using **synthetic data** influenced by **climate factors** such as temperature, humidity, solar radiation, wind speed, and precipitation.

The dataset simulates three years of daily building energy consumption.  
It is intended for **educational**, **research**, and **proof-of-concept** purposes.

---

## 🌍 Key Features
- 🧩 Synthetic climate + occupancy data generation (3 years daily)
- 🔥 Energy demand simulation (heating, cooling, occupancy effects)
- ⚙️ Linear Regression and Random Forest model training
- 📊 Model evaluation (MAE, RMSE, R²)
- 🌞 Feature importance and coefficient visualization
- 💾 Exportable dataset (`synthetic_energy_climate.csv`)
- 🧑‍🔬 Well-documented code with author metadata

---

## 🧰 Requirements
Install the following Python libraries before running the script:

```bash
pip install numpy pandas matplotlib scikit-learn python-docx
Python ≥ 3.8 is recommended.

🚀 How to Run
Clone or download this repository.

Run the script in your preferred environment (Jupyter, VSCode, or terminal):


python smart_energy_forecast.py
The script will:

Generate synthetic weather and energy data.

Train forecasting models.

Display performance plots.

Save a dataset named:

synthetic_energy_climate.csv
📊 Output Files
File	Description
synthetic_energy_climate.csv	Full synthetic dataset with features and energy consumption
Smart_Energy_Use_Forecasting.docx	Word document version of the full script and project description
smart_energy_forecast.py	Main Python script for simulation and forecasting

📈 Example Visuals
The script generates:

Energy forecast plots (Actual vs Predicted)

Feature importance bar charts

Regression coefficient plots

These help explain which climate factors most strongly influence energy use.

🧑‍💻 Author & Metadata
Author: Mr. William Tarinab0


