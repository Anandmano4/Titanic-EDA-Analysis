# Titanic-EDA-Analysis
EDA on Titanic dataset: Data cleaning, feature engineering, and visual analysis to explore survival factors.
# Titanic Data Analysis - EDA

## Overview:
This project focuses on Exploratory Data Analysis (EDA) on the Titanic dataset to uncover insights related to survival. We explore the dataset, clean missing data, visualize important relationships, and analyze correlations.

## Key Steps:
1. **Loading the Data**: Imported the Titanic dataset and previewed the first few rows.
2. **Data Cleaning**:
   - Filled missing values in `Age` (median) and `Embarked` (mode).
   - Dropped the `Cabin` column due to excessive missing values.
3. **Feature Engineering**:
   - Created `FamilySize` and `IsAlone` features.
   - Converted categorical columns (`Sex`, `Embarked`) into numeric values.
4. **Visualization**:
   - Plotted histograms, boxplots, and a correlation heatmap.
   - Visualized survival rate based on different features.
5. **Insights**:
   - Female passengers and those in 1st class had higher survival rates.
   - Passengers with family had higher survival chances compared to those traveling alone.

## Conclusion:
This EDA highlights key factors influencing Titanic survival, providing a foundation for predictive modeling in future work.

## Dependencies:
- pandas
- matplotlib
- seaborn
- scipy

---
This project aims to provide insights into survival factors and can be extended to build predictive models.
