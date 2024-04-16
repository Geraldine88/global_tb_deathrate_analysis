# Project 1: Global Analysis on Tuberculosis Death Rate

### Overview

Tuberculosis (TB) remains a significant global health concern, especially in developing countries, despite efforts to control its spread. This infectious disease, primarily affecting the lungs, is caused by the bacterium Mycobacterium tuberculosis. Understanding the factors influencing TB incidence and mortality rates is crucial for effective public health interventions. Thus, this project aims to analyze global TB data to identify trends, risk factors, and potential correlations with population characteristics and healthcare access.

The problem statement for this project is to investigate trends in tuberculosis incidence and mortality rates across different countries and regions over time. By analyzing comprehensive datasets encompassing population demographics, healthcare infrastructure, and TB-related statistics, the project seeks to uncover insights that could inform targeted interventions and policy decisions to reduce TB burden worldwide. The objective of this project is to gain a deeper understanding of the complex dynamics underlying TB epidemiology and to provide actionable insights for public health authorities and policymakers to improve TB control efforts.

---
### Data Dictionary

|**country**|object|population.csv|The name of the country being studied 

|**code**|object|tuberculosis-death-rates.csv|Country code for specific country

|**death_rate**|float|tuberculosis-death-rates.csv|The percent of adults who smoke in the respective country

|**Year**|int|tuberculosis-death-rates.csv|Year the data was taken from

|**1999_pop**|float|final_df.csv|Population in the country in the given years(1999)

|**1999_le**|float|final.csv|Life expectancy in the country in the given years(1999)

---

### Datasets

#### Provided Data

There are 3 datasets used for this project,  included in the [`data`](./data/) folder for this project.

This project used three data sources: 
1) population.csv (Population by Country) 
2) life_expectancy.csv (Life Expectancy by Country)
3) tuberculosis-death-rates.csv (Death Rate caused by Tuberculosis by country.)

**Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Exploratory Data Analysis

1) Which countries have the highest and lowest life expectancy over the course of the dataset?
2) Determine if any countries have a higher life expectancy than their population's maximum value
3) Which countries have had the lowest population growth?
4) What country had the highest death rate due to Tuberculosis in 2005?

To answer these questions, sorting and masking the final_df.csv on the appropriate columns was done, and the values were interpreted and visualized. The key finding was that there is a weak relationship between the death rate caused by tuberculosis and the decrease in population as from 2030. The two variables did not seem to be related as they had a low correlation value of 0.016. 

#### Conclusions and Recommendations

In this project, we explored trends in tuberculosis (TB) incidence and mortality rates across different countries and regions over time. We found that TB remains a significant global health concern, with some countries experiencing higher burden rates than others.
In conclusion, while TB remains a formidable public health challenge, concerted efforts at the global, national, and community levels can lead to significant progress in TB control and elimination. By implementing evidence-based strategies, leveraging innovative technologies, and prioritizing equity and social justice, we can work towards a world free of tuberculosis.
