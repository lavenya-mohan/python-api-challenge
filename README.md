# python-api-challenge - Vacation and Weather Analysis

This repository contains two Jupyter notebooks, `Weather.ipynb` and `Vacation.ipynb`, which provide a comprehensive analysis of global weather patterns and vacation opportunities by utilizing API integrations and data visualization.

---

## 1. `Weather.ipynb` - Weather Data Collection and Analysis

### Objective
The `Weather.ipynb` notebook gathers current weather data for randomly selected global cities and performs exploratory data analysis (EDA) to uncover patterns in temperature, humidity, wind speed, and cloudiness.

### Key Steps:
- **Data Collection:**  
  Weather data (temperature, humidity, cloudiness, wind speed) is collected for random cities worldwide using the OpenWeatherMap API (or a similar weather API).
  
- **Data Analysis:**  
  Several visualizations are created to analyze the relationships between:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed
  
- **Linear Regression:**  
  For both the Northern and Southern Hemispheres, linear regression models are created to analyze the relationship between weather variables and latitude.

### Outcome
The notebook provides insights into how weather conditions vary globally, showing clear trends and relationships between latitude and key weather parameters.

---

## 2. `Vacation.ipynb` - Vacation Spot Identification

### Objective
The `Vacation.ipynb` notebook uses the weather data collected in `Weather.ipynb` to identify potential vacation destinations based on specific weather criteria. It locates the nearest hotels to selected cities, providing a curated list of potential vacation spots.

### Key Steps:
- **Weather-Based Filtering:**  
  Cities are filtered based on desired weather conditions (e.g., temperature range, low humidity, minimal cloudiness).
  
- **Hotel Search:**  
  The Geoapify API is used to find the nearest hotels to each selected city that meets the ideal weather conditions.
  
- **Map Visualization:**  
  An interactive map is generated, displaying each vacation spot with details like city name, country, weather conditions, and nearby hotel options.

### Outcome
The notebook outputs a list of vacation spots around the world, each with ideal weather conditions and nearby accommodation options, providing practical resources for trip planning.

---

## Requirements
- **Python Libraries:**  
  - `matplotlib`  
  - `pandas`  
  - `requests`  
  - `hvplot`
  
- **API Keys:**  
  - OpenWeatherMap API (for weather data)  
  - Geoapify API (for hotel information)

---

## Conclusion
This project combines global weather analysis and vacation spot recommendations. Using data collection and visualization techniques, it helps users identify attractive travel destinations based on live weather data and nearby accommodation options.


