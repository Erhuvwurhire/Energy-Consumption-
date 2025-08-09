# Energy-Consumption-
Energy Consumption Forecasting and Anomaly Detection
This project applies Industrial AI techniques to analyze and forecast energy consumption data. Leveraging unsupervised learning and time series modeling, the project provides insights into usage patterns and detects anomalies in energy consumption that could indicate inefficiencies, faults, or cyber-physical risks.

Domain: Industrial Energy Analytics
Tech Stack: Python, Google Colab, Prophet, Pandas, Matplotlib
Approach: Time Series Forecasting + Anomaly Detection

## Objectives
 Forecast household or industrial energy consumption.

Detect anomalies that could indicate abnormal operations.

Demonstrate how AI can enhance energy efficiency and reliability in industrial or smart grid systems.

## Dataset
Source: UCI Machine Learning Repository – Individual household electric power consumption

Format: Time-stamped measurements of electrical variables over four years.

Variables include:

Global_active_power

Global_reactive_power

Voltage

Sub_metering_1, 2, 3

## Methods
✅ Preprocessing
Parse dates and clean missing values.

Aggregate consumption data by daily/hourly means.

**🔍 Anomaly Detection**
Use Prophet, a time series model by Meta, to learn seasonal trends.

Flag anomalies as large deviations from the model forecast.

**📊 Visualization**
Interactive plots for trends, seasonality, and outliers.

Zoom into periods of abnormal usage.

📁 Project Structure
bash
Copy
Edit
industrial-ai-energy/
│
├── energy_forecast_anomaly.ipynb     # Colab notebook
├── README.md                         # Project overview
└── data/
    └── household_power_consumption.txt (raw data)
🚀 Running the Project
Clone the repo or open the notebook in Google Colab.

Run all cells — setup, download data, and run analysis.

View time series plots and anomaly flags.

**🔎 Sample Insights**
Peak consumption during evenings and winters.

Detected outliers during holidays and equipment malfunctions.

Real-time forecasting can guide load balancing and energy optimization.

**🤖 Relevance to Industrial AI**
This project showcases how AI-driven predictive analytics can be deployed in:

Smart factories

Grid management

Industrial control systems (ICS)

Facility monitoring
