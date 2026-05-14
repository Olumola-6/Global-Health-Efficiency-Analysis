# Global Health Efficiency Analysis (2015-2023)
### Analyzing the "Health Heroes": Maximizing Life Expectancy through Smart Spending


## Table of Contents

 - [Project Overview](#project-overview)
 - [Data Source](#data-source)
 - [Tools](#tools)
 - [Data Transformation](#data-transformation)
 - [Dashboard Highlights](#dashboard-highlights)
 - [Key Insights](#key-insights)
 - [Recommendations](#recommendations)


## Project Overview
This project investigates the relationship between national health expenditure and life expectancy. The goal was to identify which countries are "Health Heroes", achieving the highest life expectancy relative to their spending and which experience "diminishing returns" on high budgets.

## Data Source 
-  **Source:** World Health Data Bank: Health Nutrition and Population Statistics (2015-2023), a dataset with 14 columns and 533 rows.


## Tools
-  Microsoft Excel (Data Cleaning)
-  Power BI: For data modeling, DAX calculations, and visualization.
-  Power Query: For the ETL (Extract, Transform, Load) process.

 
 ## Data Transformation
 -  **Used Power Query to handle NULL values, corrected data types for years and financial figures and fix naming inconsistencies (e.g., standardizing "Fed. Rep." for map accuracy).**
 -  **Pivot to Panel Data: The original "Wide" format (where years were columns) was transformed into "Long/Panel" format so that each row represents a specific Country-Year observation.**
 -  **Key Calculation:** `Efficiency Score = (Life Expectancy / Health Expenditure) * 1000`**. *To make the efficiency ratios easier to compare, i scaled the data to show the health output per $1,000 of investment.*


   <img width="1920" height="832" alt="Cleaned WORLD HEALTH ANALYSIS EXCEL" src="https://github.com/user-attachments/assets/b5e9a115-531b-4732-9928-948152d16f00" />




## Dashboard Highlights
  <img width="1560" height="871" alt="World Health ROI analysis" src="https://github.com/user-attachments/assets/f7eb79c9-82d5-4dda-89f6-0667c37e85ca" />
  *Figure 1: Current global standings spanning between 2015 - 2023.*
 


  <img width="1442" height="820" alt="Top-Performer Report" src="https://github.com/user-attachments/assets/2e1ca052-72bc-4180-bd27-0c973e6d19f9" />

 
 **Figure 2: Current global standings showing Somalia as efficiency leaders.**


 

 
 <img width="1434" height="794" alt="Bottom-Performer Report" src="https://github.com/user-attachments/assets/6de35f1e-dac2-4395-bebf-a187f8850ff2" />
 
  
  **Figure 3: Current global standings showing USA as efficiency loosers.**




 
 <img width="1442" height="795" alt="Nigeria&#39;s Analysis Report" src="https://github.com/user-attachments/assets/883ceed1-7648-46f0-ad0b-39f67908d0ee" />
  
  
  **Figure 4: Current global standings showing Nigerian's Health Efficiency.**




## Key Insights

1. **Diminishing Returns: After a certain spending threshold, the "gain" in life expectancy slows down significantly.**
2. **Efficiency is a choice: Low-income nations can achieve high "value" through prioritized primary care.**
3. **High health expenditure is not a guarantee of a long life. It is about how you spend it.**
4. **Stability of Efficiency: Countries like Somalia and Madagascar show consistent efficiency scores over the 8-year period, proving their healthcare models are resilient.**


## Recommendations

1. **Lower efficiency nations should model their primary care after our “Efficiency Leaders” like Somalia or Madagascar.**
2. **Nations should focus on community-level health interventions rather than just high-tech hospital infrastructure.**
3. **Digital Data Integration: Nations should adopt the Implementation of better data tracking (like this Power BI model) to identify waste in healthcare spending in real-time.
