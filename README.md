
## Traffic Prediction Project Overview

### Objective
The goal of this project was to develop a predictive model that accurately forecasts traffic congestion measured by speed based on a range of variables including time and weather conditions. 

### Data Description
The dataset used in this project includes various features related to traffic and environmental conditions:
(include links to dataset and more specifics about the datasets (when, where, what)
 - **Weekday (`weekday`)**: The day of the week represented as an integer (Monday=0, Sunday=6).
- **Time of Day (`time_of_day`)**: The hour of the day when the data was collected (0-23 hours).
- **Latitude (`lat`)**: Geographical latitude of the traffic data collection point.
- **Longitude (`long`)**: Geographical longitude of the traffic data collection point.

Related to the Weather:

- **Temperature (`temp`)**:  Air temperature.
- **Cloud Cover (`cloudcover`)**: The percentage of the sky covered by clouds.
- **Solar Radiation (`solarradiation`)**: The level of solar radiation in W/m².
- **Visibility (`visibility`)**: Visibility distance at the time of data collection, typically in kilometers or miles.
- **Snow Depth (`snowdepth`)**: Depth of snow on the ground at the time of data collection.
- **Precipitation (`precip`)**: Amount of precipitation during the data collection period in millimeters.
- **Wind Gust (`windgust`)**: The highest speed of the wind gusts at the time of data collection.
- **Humidity (`humidity`)**: The amount of water vapor present in the air, expressed as a percentage.
- **UV Index (`uvindex`)**: An indicator of the strength of sunburn-producing ultraviolet radiation at a particular place and time.

### Methodology
1. **Literature Review**
2. **Data Collection**: Data is sourced from historical traffic and weather records.
3. **Data Preprocessing**:
   - Cleaning: Handling missing values, removing outliers, and correcting errors.
   - Feature Engineering: Deriving new features like the day of the week, hour of the day, and encoding categorical variables such as weather conditions.
4. **Exploratory Data Analysis (EDA)**:
   - Analyzing distributions and relationships in the data.
   - Visualizing patterns and trends related to traffic flow.
5. **Model Development**:
	- Multiple Linear Regression (MLR) with Subset Selection
	- MLR with LASSO/Ridge
	- MLR with PCA
	- Linear Discriminant Analysis (LDA) ?
6. **Analysis**

### Project Outcomes
*add some cool graphics*
draft outline
1. results of our models
2. why we think they failed 
3. what the literature says and what we think could work better on a dataset like this --> future work

### How to Navigate the Project
*write something about the organization of the repo and where to find stuff*
