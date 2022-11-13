# Data-Modeling-and-Interactive-Dashboarding-using-Excel
### Aim of the project:

### Used tools:
- Excel Power Query- For data loading.
- Power Pivot in Excel - For data modeling.
- DAX - For data analysis.
- Excel Charts, Pivot Tables and Pivot Charts - To design an interactive dashboard.

### Experience gained:
Data Integration, Data Modelling, Interactive Dashboarding

### Final Output:
Dashboard in Excel
## Detailed Description
[1. Used dataset](#1-used-dataset-1)

[2. Data cleaning & Transformation ](#2-data-cleaning-&-transformation-1)

[3. Data Modeling](#3-data-modeling-1)

[4. DAX Calculations](#4-dax-calculations-1)

[5. Designing an Interactive Dashboard](https://github.com/shakhscode/Data-Modeling-and-Interactive-Dashboarding-using-Excel/blob/main/README.md#5-designing-an-interactive-dashboard)

### 1. Used dataset
### 2. Data cleaning & Transformation
### 3. Data Modelling
### 4. DAX Calculations
Total Sales = Order Quantity * Price per pizza
=order_details[quantity]*RELATED(pizzas[price])

Day and Month Name from the date column
Day :=FORMAT([date], "DDDD")
Month :=FORMAT([date], "MMM")


### 5. Designing an Interactive Dashboard
