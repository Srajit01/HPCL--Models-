# HPCL--Models-
**HPCL Green Energy Expansion Model
**
Overview

This project is part of HPCL's green energy expansion initiative, focusing on the development and optimization of renewable fuel technologies. The models developed include a Hydrogen Dispensing System, Biofuel Predictor, and a Signal Transmission System. These Python-based models aim to improve the accuracy of fuel predictions, optimize storage, and facilitate data-driven decision-making.

**Key Features**

**Hydrogen Dispensing System: **Simulates and monitors hydrogen dispensing processes to ensure efficient and safe fuel distribution.
**
Biofuel Predictor:** Predicts biofuel production and capacity based on input data, allowing for resource planning and storage optimization.

**Data Transmission System:** Collects, transmits, and stores telemetry data from sensors to ThingsBoard for real-time monitoring and visualization.

**Hydrogen Production Prediction Using Linear Regression :**

This code uses linear regression to model the relationship between energy input (kWh) and hydrogen output (kg) in a hydrogen production system. By training the model on given data points, it predicts the amount of hydrogen produced when the energy input is 100 kWh.

What It Shows:
Linear Relationship: The code assumes a linear relationship between energy input and hydrogen output.

Prediction: It demonstrates how to use a trained linear regression model to predict outputs for new input values.

Machine Learning Application: This is a simple yet practical example of applying machine learning to a real-world energy production scenario.

**Example Output:**
If the relationship holds, the model predicts the hydrogen output for 100 kWh of energy to be around 1.8 kg, continuing the linear trend from the provided data.

**Technologies Used**

Python – Core programming language for model development.

ThingsBoard – IoT platform for data visualization and telemetry management.

Flask/Django – Web interface for data input and monitoring (optional).

Pandas/Numpy – Data processing and predictive analytics.

Matplotlib/Seaborn – Data visualization and reporting.


