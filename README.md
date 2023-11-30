# EV_CO2_Project2.0
# EV_CO2_Project2.0 
#Version 2 required to resolve merge conflicts. This repo contains commits by Dia Vang, Anna Marie Estores, and Mostafa Tabatabainejad
**Project Title: "Electrifying the Roads: Analyzing the Correlation between EV Sales and CO2 Emissions Reduction"**
## Overview

This project aims to explore the potential correlation between Electric Vehicle (EV) sales and CO2 emissions. While acknowledging the multitude of variables influencing CO2 emissions, we've chosen to focus on EV sales and CO2 emissions for simplicity and efficiency, following the instructor's suggestion.

## Table of Contents

1. [Code Introduction]
2. [Data Cleaning]
3. [Correlation Analysis]
4. [Data Optimization]
5. [Conclusion]
6. [Repository Structure}.

## Code Introduction

The project utilizes Python for data manipulation, analysis, and visualization. We've employed various libraries, including Pandas for data handling, Matplotlib and Tableau for visualization. Additionally, we performed statistical analysis using Pearson correlation coefficient. Machine learning tools, such as Linear Regression, were employed for forecasting.

## Data Cleaning 

Data cleaning involved handling two separate datasets related to EV sales and CO2 emissions. Unnecessary information was dropped from both datasets, streamlining the analysis process. A challenge arose when merging the two datasets as they used different nomenclature for the United States (USA in one and United States in the other). To address this, we modified the EV sales dataset to ensure consistency and successfully merged the datasets on the "United States" label.

## Correlation Analysis

The primary objective was to assess the correlation between EV sales and CO2 emissions. Initial analysis indicated a correlation coefficient of 0.02, but after further exploration using box plots, we optimized the data and achieved an improved R-squared value of 0.61. While suggestive of a correlation, we recognize the need for additional data to strengthen this observation.

## Data Optimization

We documented the iterative changes made to optimize the model in a CSV file or within the Python script itself. The final model performance is displayed at the end of the script, providing insights into the effectiveness of the applied optimizations.

## Conclusion 

In conclusion, this project offers an initial exploration into the correlation between EV sales and CO2 emissions. Despite achieving a notable R-squared value, further data is required for robust conclusions. We've included a CSV file containing the cleaned and merged data, as well as a graph created using Tableau for additional visualization.

## Repository Structure 

- **/data:** Contains the original datasets.
- **/scripts:** Includes the Python script for data manipulation, analysis, and optimization.
- **/output:** Houses the CSV file with the cleaned and merged data.
- **/visualization:** Contains the Tableau graph for enhanced visualization.

Feel free to explore the code, data, and visualizations within the respective folders.

For any questions or additional information, please contact the project contributors.

**Note:** The project is an ongoing exploration, and we welcome collaboration and feedback to enhance its depth and reliability.
g.

**Objective:**
Examine the trend of increasing electric vehicle (EV) sales and investigate whether this growth is associated with a corresponding reduction in CO2 emissions in a given region.

**Key Components:**

1. **Data Collection:**
   - Gather data on EV sales over time, including the type and model of vehicles.
   - Collect data on CO2 emissions from various sources, such as power plants and industrial facilities.

2. **Geographical Analysis:**
   - Segment the data by region to assess EV sales and CO2 emissions reduction in the USA specifically.

3. **Temporal Trends:**
   - Analyze temporal trends to identify periods of increased EV sales and any corresponding changes in CO2 emissions.

4. **Correlation Analysis:**
   - Use statistical methods to determine the correlation between the increase in EV sales and changes in CO2 emissions.

5. **Visualization:**
   - Create visualizations using Python (Pandas, Matplotlib) to illustrate the relationship between EV sales and CO2 emissions.

6. **Forecasting:**
   - Utilize machine learning algorithms to forecast future trends in EV sales and predict potential impacts on CO2 emissions.

7. **Policy Implications:**
   - Investigate the influence of government incentives or policies on EV adoption and emissions reduction.

**Dataset Sources:**
   - EV sales data from automotive industry reports, dealerships, or government agencies.
   - CO2 emissions data from environmental agencies, power plants, and industrial sources.

**Considerations:** (for future project coollaberation)
   - Factor in the electricity grid's carbon intensity to assess the environmental impact of EVs.
   - Consider external factors like changes in energy policies, economic conditions, and technological advancements.

**Benefits:**
   - Provide insights into the effectiveness of EV adoption in reducing overall CO2 emissions.
   - Offer policymakers and stakeholders data-driven information for sustainable transportation planning.

**Technologies:**
   - Python (Pandas, Matplotlib), SQL (for data storage and retrieval), and machine learning for predictive analysis and trend forecasting.
# Electric Vehicle Sales and CO2 Emissions Correlation Analysis
