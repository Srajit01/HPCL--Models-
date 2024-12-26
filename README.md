# HPCL--Models-
**HPCL Green Energy Expansion Model**

Overview

This project is part of HPCL's green energy expansion initiative, focusing on the development and optimization of renewable fuel technologies. The models developed include a Hydrogen Dispensing System, Biofuel Predictor, and a Signal Transmission System. These Python-based models aim to improve the accuracy of fuel predictions, optimize storage, and facilitate data-driven decision-making.

**Key Features**

**1) Hydrogen Dispensing System:** Simulates and monitors hydrogen dispensing processes to ensure efficient and safe fuel distribution.

**2) Biofuel Predictor:** Predicts biofuel production and capacity based on input data, allowing for resource planning and storage optimization.

**3) Data Transmission System:** Collects, transmits, and stores telemetry data from sensors to ThingsBoard for real-time monitoring and visualization.

**4) Hydrogen Production Prediction Using Linear Regression :**

This code uses linear regression to model the relationship between energy input (kWh) and hydrogen output (kg) in a hydrogen production system. By training the model on given data points, it predicts the amount of hydrogen produced when the energy input is 100 kWh.

**5) Arduino Sensor Data Logger for Hydrogen System".**

**What the Code Does:**
The code reads data from three analog sensors connected to an Arduino (or compatible microcontroller) to monitor the temperature, pressure, and flow rate of a system, likely related to hydrogen production or dispensing. The sensors output analog signals, which are then converted to meaningful physical quantities (temperature in °C, pressure in bar, and flow rate in L/min).

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


