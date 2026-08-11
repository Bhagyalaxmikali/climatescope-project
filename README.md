
# ClimateScope – Global Weather Trends & Extreme Events

ClimateScope is an interactive data visualization dashboard developed as part of the **Infosys Springboard Virtual Internship 6.0**. It analyzes global weather patterns, seasonal trends, regional variations, air quality, and extreme weather events.

## Features

- Global weather trend analysis
- Monthly, yearly and seasonal analysis
- Extreme temperature event detection
- Air quality analysis
- Country-wise comparisons
- Interactive charts and visualizations
- Downloadable reports

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Streamlit
- Scikit-learn

## Dataset

**Global Weather Repository** – Kaggle

The dataset contains weather and air-quality information such as temperature, humidity, wind speed, precipitation, PM2.5, PM10 and carbon monoxide.

## Project Workflow

Data Collection → Data Cleaning → Data Preprocessing → Data Analysis → Visualization → Streamlit Dashboard

## Key Analysis

- Temperature trends
- Seasonal weather patterns
- Regional comparisons
- Temperature vs. air quality
- Extreme events using 95th and 99th percentile thresholds

## Project Structure

climatescope-project/
├── app.py
├── dashboard.py
├── data_analysis_visualization.ipynb
├── data_cleaning_climatescope_1.ipynb
├── requirements.txt
├── weather_daily.csv
├── weather_data_monthly.csv
├── weather_seasonal_avg.csv
└── weather_yearly_avg.csv

How to Run

1.git clone https://github.com/Bhagyalaxmikali/climatescope-project.git

2.cd climatescope-project

3.pip install -r requirements.txt

4.streamlit run app.py
