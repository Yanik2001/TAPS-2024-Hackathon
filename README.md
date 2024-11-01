### TAPS-2024-Hackathon

# Overview

This project consists of four interconnected Jupyter notebooks designed to monitor and analyze weather, soil and irrigation data. The main entry point is the Landing_page.ipynb, which serves as a dashboard to navigate between other notebooks, each providing specific insights into weather conditions, soil characteristics, and irrigation data. The entire suite helps automate decision-making for agricultural processes, such as irrigation scheduling, by utilizing interactive plots and data analysis.

# Notebooks Description

## Landing Page (Landing_page.ipynb)

This is the main interface for the project. It acts as a main component to navigate between different data analysis notebooks. Each created section in this notebook links to a specific notebook that analyzes various environmental parameters. It also provides an overview of the system, allowing easy access to different aspects of data analysis.

## Weather Data (Weather_data.ipynb)

This notebook focuses on organizing, cleaning and developing weather data, including precipitation, air temperature, and other atmospheric conditions. It brings insights after considering various weather factors. It includes interactive visualizations that help users understand the relationships between weather parameters and their effect on the environment.

## Soil Data (Soil_data.ipynb)

The Soil_data.ipynb notebook is used for analyzing soil characteristics, including the nutrients that are present in the soil. The goal is to monitor soil conditions to determine the health of the soil. This notebook is instrumental in understanding the current state of the soil in response to varying environmental conditions.

## Irrigation Data (Irrigation_data.ipynb)

This notebook provides insights into the irrigation system by analyzing water use and efficiency metrics. It works in conjunction with soil and weather data to create an automated irrigation schedule, aiming to optimize water use based on real-time environmental and soil parameters.

# Usage

Start by opening the Landing_page.ipynb notebook. This serves as the control center to access other notebooks.

Use the buttons on the landing page to open Weather_data.ipynb, Soil_data.ipynb, or Irrigation_data.ipynb.

Each notebook contains interactive plots and analyses to provide insights into different aspects of agricultural data.

The notebooks work together to provide a complete picture of environmental conditions and irrigation needs, helping optimize decision-making for crop management.

# Requirements

Python 3.x

Jupyter Notebook

Libraries: pandas, matplotlib, plotly, panel, and any other dependencies as specified in each notebook's import statements.

Future Improvements

Integration of machine learning models to predict irrigation requirements based on historical data.

Adding support for additional sensors and expanding the coverage of environmental parameters.

# Authors

Eliana Samudio - Bachelor of Science in Agricultural Technology Management
Yanik Sitta - Master´s of Science in Data Analytics
