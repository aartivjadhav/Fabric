## About the Data

This report uses publicly available data from the WHO Global Health Observatory (GHO), accessed via REST APIs.

Two datasets were used in this analysis:

• Life Expectancy Dataset  
Source: https://ghoapi.azureedge.net/api/WHOSIS_000001  
This dataset contains global life expectancy estimates across countries, regions, genders, and years.

• Hospital Beds Dataset  
Source: https://ghoapi.azureedge.net/api/WHS4_100  
This dataset provides hospital bed availability per 10,000 population across countries and years.

The data has been transformed and modelled in Microsoft Fabric using a structured semantic model to enable analysis across time, geography and demographic dimensions.

Life Expectancy Dataset (Indicator: WHOSIS_000001): Tracks the average number of years a newborn is expected to live if prevailing patterns of mortality at the time of birth remain constant. It serves as a foundational metric for assessing overall population health, quality of life and healthcare outcomes across different geographic territories and demographics.

Project Insights - 
Key Insights & Findings - 

Life Expectancy Analysis - 
1) Global Leaders and Lowest Performers- 

Between 2000 and 2021, Japan recorded the highest average life expectancy at 83.16 years, reflecting strong healthcare systems and favorable living conditions. In contrast, Lesotho reported the lowest average life expectancy at 48.09 years, highlighting significant health and socioeconomic challenges.

2) Improvement Over Time -

Average life expectancy showed a consistent upward trend from 2000 onwards, indicating overall improvements in global healthcare access and living standards across many countries.

3) Regional Differences -

Life expectancy varies considerably across regions. The European Region recorded the highest average life expectancy, while the African Region had the lowest, reflecting disparities in healthcare infrastructure, economic development and public health outcomes.

4) Gender-Based Trends -

Females recorded the highest average life expectancy among all gender categories, with an average of 72.61 years between 2000 and 2021. This trend is consistent with global demographic patterns where women generally have longer life expectancy than men.

5) Peak and Decline During the Pandemic Period -

Average life expectancy reached its highest level in 2019 at 72.63 years. However, a decline was observed in 2020 and 2021, which may reflect the global health impacts experienced during the COVID-19 pandemic period.

Confidence Interval Analysis -

1) Data Certainty Over Time

The average confidence interval for life expectancy estimates was lowest in 2019 (0.90), indicating greater certainty in the reported figures. The highest average confidence interval was observed in 2021 (1.14), suggesting increased variability and uncertainty in health estimates during that period.

Hospital Bed Analysis - 

1) Countries with Highest Healthcare Capacity -

Oman, Luxembourg, Iran and Hungary recorded the highest average hospital bed availability, with approximately 99 hospital beds per 10,000 population, indicating strong healthcare infrastructure and capacity.

2) Country with Lowest Healthcare Capacity -

Chad recorded the lowest average hospital bed availability at approximately 40 beds per 10,000 population, highlighting potential constraints in healthcare resources and accessibility.

3) Hospital Bed Trends Over Time -

Average hospital bed availability fluctuated across the study period. The highest average was recorded in 2012 with 89.31 beds per 10,000 population, while the lowest average was observed in 2021 with 85.33 beds per 10,000 population, indicating a gradual decline in available hospital bed capacity over recent years.
