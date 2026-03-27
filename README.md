# 🚲 Citi Bike and Weather Exploratory Data Analysis (Jersey City)

**Authors:** Weiyi Lu & Liuyang Bai

## Project Overview
This project is an Exploratory Data Analysis (EDA) that investigates how meteorological conditions influence Citi Bike usage patterns in Jersey City. By integrating mobility records with localized weather data, we quantify the sensitivity of urban cycling behavior to temperature, precipitation, and wind speed, and examine how commuting and leisure trips respond differently to these external factors.

## Datasets
1. **Jersey City Citi Bike System Data:** Trip-level mobility records managed by Lyft. It includes ride IDs, bike types (classic vs. electric), precise timestamps, spatial details, and user status (Annual Member vs. Casual).
2. **Open-Meteo Historical Weather API:** Localized hourly and daily atmospheric readings, including temperature, precipitation, and wind speed.

## Key Analyses
* **Temporal Distributions:** Daily, weekly, and seasonal variations in ride volume.
* **Overall Weather Impacts:** Aggregate effects of temperature, rain, and wind on daily ridership.
* **Hourly Commute Patterns:** Comparing weekday commuting trends (bimodal rush hours) against weekend leisure trends (single afternoon peak) under varying weather conditions.
* **User Segmentation:** Behavioral differences between Annual Members and Casual riders.
* **Rideable Type Preferences:** Analyzing the shifting proportion of electric bike (e-bike) usage during challenging weather.

## Key Findings
* **Temperature is the Primary Driver:** Ridership grows steadily as temperatures rise, though it experiences a slight dip on extremely hot days (over 25°C).
* **Commuter-Centric System:** The system is fundamentally utilized for commuting. Weekdays feature sharp morning and evening rush hour peaks heavily dominated by annual members.
* **Rain is the Strongest Deterrent:** Precipitation causes the most significant drops in total rides. While light rain lowers overall volume, heavy rain actively disrupts the typical weekday morning rush hour.
* **Commuter Resilience to Wind:** Wind reduces ridership by increasing physical difficulty. However, moderate wind mostly discourages weekend leisure riders, whereas extreme wind is required to noticeably reduce weekday commutes.
* **Strategic E-Bike Usage:** Users actively prefer electric bikes when facing strong winds, relying on motor assistance to overcome physical resistance. Interestingly, the proportion of e-bike rides remains largely unchanged during hot or rainy weather.

## Repository Structure
* `Midterm_Project.ipynb`: The core Jupyter Notebook containing all data processing, EDA, and data visualizations.
* `report.pdf`: The detailed final report documenting the methodology, figures, and comprehensive conclusions.
