# Aviation Risk Analysis Project

## Overview

This analysis aims to help the company expand into the aviation industry by the accident that have occurred over the years.The aim of the analysis is to help the company determine which aircraft will present the lowest risk for the company. The data used for this analysis comes from the [National Database Accident Database](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) and it coverers all civil aviation accidents and selected incidents from 1962 to 2023.
the objective is to clean, analyze, and visualize the data to produce actionable business recomendation that can guide the purchase decision for aircraft.

## Business Understanding

The company is interested in diversifying into the aviation sector but lacks insight into the risks involved in operating different aircraft. The primary stakeholder for this project is the head of the company's new aviation division. The key business questions to address are:
- Which aircraft models have the lowest risk of accidents or incidents?
- Are there specific aircraft characteristics (e.g., year, size) that correlate with a lower accident rate?
- What recommendations can be made to minimize operational risks in this new venture?

## Data Understanding and Analysis

### Data Source
The dataset used in this project comes from the National Transportation Safety Board (NTSB) and contains data on aviation accidents and incidents involving civil aviation from 1962 to 2023. The dataset includes fields such as:
- Accident Date
- Aircraft Model
- Severity of Accident (fatal, non-fatal)
- Aircraft Size (small, large)
- Location
- Additional metadata such as weather conditions, flight phases, etc.

### Data Cleaning and Preparation
Missing values were handled by appropriate imputation methods, and the dataset was cleaned to ensure consistency and accuracy before analysis. Outliers were investigated, and non-relevant columns were removed to focus on variables directly related to the risk of accidents.

### Visualizations
1. **Accident Frequency by Aircraft Model**: A bar chart showing which aircraft models have the highest and lowest accident frequencies.
2. **Trend of Accidents Over Time**: A line graph showing how accident rates have changed over the years for different aircraft.
3. **Risk Factors Correlation**: A heatmap indicating correlations between various factors (aircraft size, weather, time of day) and accident risk.

### Business Recommendations
Based on the analysis, the following three recommendations can be made for minimizing risks when expanding into the aviation sector:
1. **Prioritize newer models with lower accident rates**: Certain aircraft models, especially newer ones, consistently show a lower frequency of accidents. These should be prioritized for purchase.
2. **Smaller aircraft have fewer incidents overall**: Smaller planes seem to have fewer severe accidents compared to larger planes, making them a safer bet for initial investment.
3. **Time of day and weather considerations**: Data indicates a correlation between accidents and certain flight conditions, such as poor weather or night flights. This should be factored into operational planning.

## Conclusion

Through this analysis, we have identified clear patterns that can guide the company's entry into the aviation industry. By selecting aircraft with a history of lower accident rates and optimizing for safer operational conditions, the company can reduce the risk of entering this new market.

---

### Repository Structure
