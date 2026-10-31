# dashbords-for-matplotlib-seaborn-and-folium
# Create Visualizations using Matplotlib, Seaborn and Folium

In this assignment, you will have the opportunity to demonstrate the skills you have acquired in creating visualizations using *Matplotlib, Seaborn, and Folium*

## Table of Contents
1. [Objectives](#objectives)
2. [Setup](#setup)
   - [Installing Required Libraries](#installing-required-libraries)
   - [Importing Required Libraries](#importing-required-libraries)
3. [Scenario](#scenario)
   - [Data Description](#data-description)
4. [Importing Data](#importing-data)
5. [Creating Visualizations for Data Analysis](#creating-visualizations-for-data-analysis)
## Objectives
After completing this lab, you will be able to:
- Create informative and visually appealing plots with Matplotlib and Seaborn.
- Apply visualization to communicate insights from the data.
- Analyze data through using visualizations.
- Customize visualizations

### Installing Required Libraries
The following libraries are required for this lab:
* `pandas` for managing data.
* `numpy` for mathematical operations.
* `matplotlib` for plotting.
* `seaborn` for plotting.
* `folium` for plotting.
  
import numpy as np
import pandas as pd
import matplotlib as mpl
import matplotlib.pyplot as plt
import seaborn as sns
import folium

%matplotlib inline

Date: Month-end date of sales observation.

Recession: Binary variable (1 = recession, 0 = normal).

Automobile_Sales: Number of vehicles sold.

GDP: Per capita GDP value in USD.

Unemployment_Rate: Monthly unemployment rate.

Consumer_Confidence: Synthetic index representing consumer confidence.

Seasonality_Weight: Seasonal effect weight on automobile sales.

Price: Average vehicle price.

Advertising_Expenditure: Company advertising expenditure.

Vehicle_Type: Type of vehicles sold (Superminicar, Smallfamilycar, Mediumfamilycar, Executivecar, Sports).

Competition: Measure of competition in the market.

Month: Extracted month.

Year: Extracted year.



You can install them using pip:
```bash
pip install pandas numpy seaborn matplotlib folium
