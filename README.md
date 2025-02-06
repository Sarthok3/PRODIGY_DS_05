# **DATA-DRIVEN INSIGHTS ON ACCIDENT SEVERITY AND CONTRIBUTING FACTORS** #

The provided code performs an extensive exploratory data analysis (EDA) on a U.S. accidents dataset (US_Accidents_March23.csv) using Python libraries such as pandas, matplotlib, and seaborn.

1. **Data Loading and Initial Exploration**:
- Loads the dataset and inspects the first few rows using `df.head()`.
- Prints column information and checks the data types with `df.info()`.
- Counts the number of columns, rows, and numeric data types.

2. **Missing Data Handling**:
Identifies missing data percentages and visualizes them using a horizontal `bar plot`.

4. **City-Based Analysis**:
- Extracts unique city names and counts accidents by city.
- Visualizes accident distribution across top cities using bar plots and distributions.

5. **Temporal Analysis**:
- Converts the Start_Time column to datetime and extracts temporal features like day, month, and hour.
- Visualizes accident density by hour and day of the week.

6. **Geospatial Analysis**:
Uses scatter plots to visualize accident locations based on `latitude` and `longitude`, with additional coloring by state and severity.

7. **Severity-Based Analysis**:
Creates `pie charts` to visualize accident distribution for each severity level (1 to 4).

8. **Sampling and Weather Conditions**:
- Selects a sample of 10,000 records for further analysis.
- Analyzes the relationship between accident severity and visibility.
- Visualizes weather conditions contributing to high accident counts.

9. **Environmental and Road Feature Analysis**:
Groups road features like Amenity, Bump, Crossing, and Railway by severity level and plots bar charts.

10. **State and City Accident Distribution**:
Visualizes accident counts by state and top 50 cities.

11. **Pandemic Impact (2020 Data)**:
- Filters data for the year 2020 and analyzes monthly accident counts.
- Annotates the plot to highlight the impact of the COVID-19 pandemic.

## **Key Objective:** ##
The key objective is to analyze and visualize US accident data, exploring accident frequency, severity, temporal patterns, weather conditions, and geographical distributions to uncover insights and trends for better understanding and decision-making in traffic safety.
