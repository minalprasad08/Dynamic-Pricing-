Dynamic Pricing for Urban Parking Lots : 
Capstone Project – Summer Analytics 2025

By: Minal Prasad
Hosted by: Consulting & Analytics Club × Pathway

Project Overview : 
This project implements a real-time, intelligent dynamic pricing engine for 14 urban parking spaces over a simulated period of 73 days. The objective is to maximize parking lot efficiency by adjusting prices based on real-time conditions such as:
Occupancy rate
-Queue length
-Traffic congestion nearby
-Vehicle type
-Special day indicators

Models Implemented : 
🔹 Model 1: Baseline Linear Pricing
A simple model that increases the price linearly with occupancy rate.

🔹 Model 2: Demand-Based Pricing
A more advanced model using a custom demand function that incorporates multiple real-time features. The final price is calculated using a normalized demand score and is bounded to ensure smooth transitions.

Tools & Technologies :
Python 
Pandas, NumPy for data processing
Bokeh for real-time interactive visualizations
Google Colab for development
CSV export for downstream use

Key Features :
Smooth and explainable price changes
Real-time visualization with Bokeh
Exportable dynamic pricing predictions for further analysis
Clean and scalable codebase, with feature engineering and pricing logic modularized

 Future Work :
Model 3: Competitive pricing using geographic proximity and competitor prices
Rerouting logic: Suggest alternate lots when a parking space is full
Pathway integration: Real-time data streaming with Pathway's event engine

Acknowledgements :
Thanks to the Consulting & Analytics Club, IITG and Pathway for organizing the Summer Analytics 2025 program and providing this industry-relevant capstone challenge.











