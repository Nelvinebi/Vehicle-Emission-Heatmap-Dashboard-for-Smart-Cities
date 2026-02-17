Vehicle Emission Heatmap Dashboard for Smart Cities

This project simulates vehicle emissions in an urban environment and visualizes them through an interactive Streamlit dashboard. Using synthetic data, it generates GPS traces, vehicle speeds, and pollutant levels (CO₂, NO₂, CO, PM2.5), and maps them as a 3D heatmap with supporting analytics.

Features

Generates synthetic vehicle data with >100 points (default: 5000).

Simulates pollutants: CO₂, NO₂, CO, and PM2.5.

Interactive filters: pollutant type, time of day, vehicle types, and speed ranges.

Visualizes emissions with PyDeck Hexagon heatmaps.

Displays KPIs (average speed, total emissions, peak emission hour).

Includes charts for emissions by hour and vehicle type.

Export filtered datasets to CSV or Excel.

Installation

Clone the repository and install dependencies:

git clone https://github.com/yourusername/Vehicle-Emission-Heatmap-Dashboard.git
cd Vehicle-Emission-Heatmap-Dashboard
pip install -r requirements.txt


Dependencies:

Python 3.8+

Streamlit

Pandas

NumPy

PyDeck

Matplotlib

OpenPyXL (for Excel export)

Usage

Run the dashboard locally:

streamlit run vehicle_emission_heatmap_dashboard.py

Example Dataset

A sample dataset is provided:
📂 synthetic_vehicle_emissions.xlsx

Columns:

timestamp – sample time

lat, lon – GPS coordinates

speed_kph – vehicle speed

vehicle_type – car, bus, truck, motorcycle, ridehail

CO2_gps, NO2_mgps, CO_mgps, PM25_mgps – pollutant levels

hour – hour of the day

city – city label

Applications

Smart city planning and air quality monitoring.

Testing emission reduction policies.

Demonstrating IoT mobility dashboards.

Educational use for data visualization and geospatial analytics.

AUthor [ Name: Agbozu Ebingiye Nelvin

         Github: https://github.com/Nelvinebi/ 
         
         LinkedIn: *https://www.linkedin.com/in/agbozu-ebi/
         ]

License

MIT License – see LICENSE.
