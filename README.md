# Heat Pump Demand Forecasting
This project focuses on analyzing and forecasting electricity consumption for residential heat pumps using real-world, time-series data. The aim is to develop a predictive model that can estimate half-hourly electricity usage, helping to better understand energy demands across different properties and conditions.

📁 Dataset Overview
The dataset includes three main components:

## Heat Pump Consumption

- Half-hourly electricity usage (kWh)

- Timestamps from 2024-01-01 to 2024-12-31

- Unique identifiers for each heat pump

## External Temperature

- Half-hourly temperature readings (°C)

- Matched by location ID and timestamp

## Property Metadata

- Property type, size, insulation, and more

- One row per heat pump

🔍 Project Objectives
Perform exploratory data analysis to identify trends and anomalies

Engineer features to enhance model predictive power

Build and evaluate forecasting models for electricity consumption


🛠 Tools & Techniques
Python, Pandas, NumPy, scikit-learn, XGBoost.

Time series analysis & forecasting

Feature engineering (e.g., degree days, time-of-day indicators)

Model evaluation using metrics like RMSE


1. Create a virtual environment and activate it:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

2. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

3. Open the Notebook:

    ```sh
    src/main.ipynb
    ```