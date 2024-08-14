# Data Science Internship Task 4: Traffic Accident Data Analysis

## Overview

This project involves analyzing and visualizing traffic accident data to identify patterns related to road conditions, weather, and time of day. The primary objective is to derive actionable insights from the data and present these insights through various visualizations.

## Dataset

The dataset used for this analysis is `dataset.csv`, which includes traffic accident records with the following features:

- **Road Surface**: Type of surface where the accident occurred.
- **Weather Conditions**: Weather conditions at the time of the accident.
- **Time (24hr)**: The time of day when the accident happened.
- **Casualty Severity**: Severity level of the accidents.

## Task Description

The main objectives of this task are:

1. **Data Preparation**
   - **Load the Dataset**: Import the `dataset.csv` into a Pandas DataFrame for analysis.
   - **Inspect the Data**: Review the dataset's structure and content to understand its features and target variables.
   - **Preprocess the Data**: Convert time data to a suitable format and handle any missing values if present.

2. **Data Visualization**
   - **Accidents by Road Surface Conditions**: Create a bar plot to visualize the distribution of accidents based on different road surface conditions.
   - **Accidents by Weather Conditions**: Generate a bar plot to show the number of accidents under various weather conditions.
   - **Accidents by Time of Day**: Create a histogram to illustrate the frequency of accidents at different hours of the day.
   - **Correlation Matrix of Numerical Variables**: Plot a heatmap to visualize the correlation between numerical variables in the dataset.
   - **Accidents by Severity**: Generate a pie chart to depict the proportion of accidents by severity.

## Steps Implemented

1. **Import Necessary Libraries**
   - Libraries for data manipulation (`Pandas`), visualization (`Matplotlib` and `Seaborn`), and geospatial data handling (`Folium` and `Geopandas`) are used to support data analysis and visualization tasks.

2. **Load and Inspect the Dataset**
   - The dataset is loaded into a DataFrame, and its structure is inspected to understand its columns and the first few rows of data.

3. **Preprocess the Data**
   - The `Time (24hr)` column is converted to datetime format to extract hour information. Data is cleaned and prepared for analysis.

4. **Visualization**
   - **Accidents by Road Surface Conditions**: A bar plot is created to visualize the distribution of accidents based on road surface conditions.
   - **Accidents by Weather Conditions**: A bar plot is generated to show the distribution of accidents across different weather conditions.
   - **Accidents by Time of Day**: A histogram is plotted to display the frequency of accidents at different times of the day.
   - **Correlation Matrix**: A heatmap of the correlation matrix is created for numerical variables.
   - **Accidents by Severity**: A pie chart is plotted to show the proportion of accidents based on severity levels.

## Results

- **Accidents by Road Surface Conditions**
  - The bar plot provides insight into how different road surface conditions contribute to the frequency of accidents.

- **Accidents by Weather Conditions**
  - The bar plot illustrates the impact of various weather conditions on the number of accidents.

- **Accidents by Time of Day**
  - The histogram shows the distribution of accidents throughout the day, highlighting peak times.

- **Correlation Matrix**
  - The heatmap reveals relationships between numerical variables in the dataset.

- **Accidents by Severity**
  - The pie chart shows the distribution of accident severity levels, indicating the proportion of each severity type.

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualizations of accident data.
- **Seaborn**: For enhanced plotting capabilities and visualization aesthetics.
- **Folium**: For geographic visualizations and heatmaps (optional for additional spatial analysis).
- **Geopandas**: For handling geospatial data (optional for additional spatial analysis).
