Project Title - 
WHO Global Health Analytics Dashboard (2000–2021)

Author: Aarti Kadam  
Role: Data Analyst

Project Overview -
This project analyzes global health indicators using data from the WHO Global Health Observatory (GHO). 
It focuses on life expectancy trends, healthcare infrastructure and regional disparities across countries from 2000 to 2021.
The dashboard is built using Microsoft Fabric and Power BI with a structured semantic model to enable interactive analysis across time, geography and demographic dimensions.

Data Sources -
Data is sourced from the WHO Global Health Observatory (GHO) via REST APIs:

• Life Expectancy Dataset  
https://ghoapi.azureedge.net/api/WHOSIS_000001  

• Hospital Beds Dataset  
https://ghoapi.azureedge.net/api/WHS4_100  

Tools & Technologies -
- Microsoft Fabric
- PySpark Notebook
- Medallion Architecture
- Power BI
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- REST APIs (WHO GHO)

Screenshots -
![Executive Dashboard](screenshots/executive.png)
![Insights Page](screenshots/insights.png)
![Drillthrough Page](screenshots/drillthrough.png)

Key Insights - 
• Japan recorded the highest average life expectancy (83.16 years), while Lesotho recorded the lowest (48.09 years).
• Life expectancy showed a consistent upward trend from 2000 to 2019, followed by a decline during 2020–2021.
• Europe had the highest regional life expectancy, while Africa had the lowest.
• Females had higher average life expectancy (72.61 years) compared to other gender groups.
• Hospital bed availability was highest in Oman, Luxembourg, Iran, and Hungary (~99 per 10,000 population).
• Chad recorded the lowest hospital bed availability (~40 per 10,000 population).
• Global hospital bed availability declined slightly from 2012 to 2021.
Refer to - Documents/Project_summary.md

Project Features -
- Interactive Executive Dashboard
- Drill-through analysis (Country-level insights)
- Trend analysis across years (2000–2021)
- Regional comparison of health indicators
- Confidence interval analysis for data reliability

Key Learning / Outcome -
This project demonstrates end-to-end data analytics workflow including data ingestion, transformation, modeling and visualization using Microsoft Fabric and Power BI. It highlights skills in data modeling, DAX and storytelling through data.

End-to-End Flow Summary - 
API Source → Bronze (Raw data ingested via PySpark notebooks) → Silver (Cleaned using PySpark notebooks) → Gold (Validated and modeled data) → Power BI Semantic Model → Power BI Report (Dashboard)
