# Electric Vehicle Population Data Analysis

## Project Overview

This project analyzes the Electric Vehicle Population Data from the Washington State Department of Licensing. The analysis focuses on understanding electric vehicle types, manufacturers, models, model years, geographic distribution, and electric range using exploratory data analysis and statistical techniques.

## Objective

To analyze the Electric Vehicle Population Data using descriptive statistics and data visualization to identify trends, patterns, and key insights.

## Research Questions

1. What are the key trends and patterns in the Electric Vehicle Population Data?
2. Which electric vehicle types and manufacturers are the most common in the dataset?

## Dataset

**Source:** Data.gov – Electric Vehicle Population Data  
**Publisher:** Washington State Department of Licensing  
**Dataset:** Electric Vehicle Population Data

The dataset contains information about Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered in Washington State.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Analysis Performed

- Exploratory Data Analysis
- Data Cleaning
- Electric Vehicle Type Analysis
- Top 10 Manufacturers Analysis
- Top 10 Models Analysis
- Model Year Trend Analysis
- Top 10 Counties Analysis
- Electric Range Analysis
- Descriptive Statistics
- Skewness and Kurtosis Analysis
- Correlation Analysis
- BEV vs PHEV Manufacturer Analysis
- BEV vs PHEV Model Year Analysis
- Average Electric Range by EV Type
- Hypothesis Testing using Independent T-Test

## Key Findings

- Battery Electric Vehicles (BEVs) are significantly more common than Plug-in Hybrid Electric Vehicles (PHEVs).
- Tesla is the most common manufacturer in the dataset.
- Tesla Model Y is the most common EV model.
- The 2023 model year has the highest number of vehicles in the dataset.
- King County has the highest EV population among the analyzed counties.
- Vehicles with recorded positive electric range have an average range of approximately 107 miles.
- BEVs have a substantially higher average electric range than PHEVs.
- There is a weak negative correlation between Model Year and Electric Range.
- The independent t-test indicates a statistically significant difference in electric range between BEVs and PHEVs.

## Statistical Analysis

An independent t-test was performed to compare the electric range of BEVs and PHEVs.

- **t-statistic:** 489.62
- **p-value:** < 0.05

The result indicates a statistically significant difference in electric range between BEVs and PHEVs.

## Conclusion

This project provides insights into the characteristics and distribution of electric vehicles in Washington State. The analysis shows that BEVs dominate the dataset, with Tesla being the most common manufacturer and Model Y being the most common model. EVs are concentrated in recent model years, while King County has the highest EV population. Statistical analysis also shows considerable variation in electric range and a significant difference in range between BEVs and PHEVs.
