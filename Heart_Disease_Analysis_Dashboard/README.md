# Heart Disease Analysis Dashboard

## Overview

The **Heart Disease Analysis Dashboard** is an interactive Power BI report designed to provide detailed insights into cardiovascular health trends. This dashboard empowers healthcare professionals and decision-makers to analyze patient demographics, medical metrics, and risk factors associated with heart disease.

## Features

### Key Metrics
- **Average Age**: Displays the average age of patients.
- **Cholesterol Levels**: Tracks patient cholesterol levels categorized into "Low", "Normal", and "High".
- **Gender Distribution**: Highlights the proportion of male and female patients.
- **Heart Disease Cases**: Visualizes the count of patients diagnosed with heart disease (`num`).
- **Age Group Analysis**: Segments patients into distinct age groups for better demographic insights.

### Visualizations
1. **Cholesterol Levels by Age Group**: Provides insights into cholesterol trends across different age demographics.
2. **Heart Disease Analysis by Gender**: Compares the prevalence of heart disease between male and female patients.
3. **Age vs. Cholesterol Category**: Explores the relationship between patient age and cholesterol levels.
4. **Heart Disease Breakdown**: Visualizes the distribution of heart disease cases (`num`) across various demographics.
5. **Patient Distribution by Age Group**: Displays the overall distribution of patients by predefined age categories.

### Interactive Filters
- **Age Group Filter**: Focus on specific age ranges such as 30-40, 40-50, etc.
- **Gender Filter**: Narrow down analysis to male or female patients.
- **Reset Button**: Easily revert all filters to their default state.

## Data Details

The dashboard is powered by the `HeartDisease.csv` file, which contains the following key columns:

- **Patient Information**: `age`, `sex` (0 = female, 1 = male)
- **Medical Metrics**: `cp` (chest pain type), `trestbps` (resting blood pressure), `chol` (cholesterol levels)
- **Derived Metrics**: `cholesterol_category` ("Low", "Normal", "High"), `age_grp` (segmented age groups)
- **Diagnosis**: `num` (heart disease diagnosis, 0 = no, 1 = yes)

## Requirements

To use this dashboard, ensure the following:

1. **Power BI Desktop**: Download and install the latest version from [Microsoft Power BI](https://powerbi.microsoft.com/).
2. **Data Source**: Place the `HeartDisease.csv` file in an accessible location and ensure the Power BI file's data connections are updated.

## Setup Instructions

1. Open the `Heart_Disease_Analysis_Dashboard.pbix` file in Power BI Desktop.
2. Refresh the data to load the latest updates from `HeartDisease.csv`.
3. Use the interactive filters and visuals to explore health insights.

## Usage

This dashboard is ideal for:

- **Healthcare Professionals**: To analyze patient health metrics and identify trends in cardiovascular health.
- **Researchers**: To study the correlation between patient demographics and heart disease risk factors.
- **Public Health Analysts**: To gain insights for improving community health initiatives.

## Dashboard

![image](https://github.com/user-attachments/assets/ff91b3e6-1425-4125-885b-3a06b22a2618)


## Contribution

Contributions are welcome! If you have suggestions for improvement or encounter any issues, feel free to open an issue or submit a pull request.
