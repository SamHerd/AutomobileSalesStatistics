# 🚗 Vehicle Sales and Unemployment Rate Analysis During Recession

This project analyzes the historical trends in automobile sales during recession periods, providing insights into how sales were affected by factors such as the unemployment rate, GDP, consumer confidence, and advertising expenditure. 

---

## 📌 **Objectives**
- Analyze the impact of recession periods on vehicle sales.  
- Compare trends between different vehicle types.  
- Create interactive and informative visualizations using **Matplotlib**, **Seaborn**, **Folium**, and **Plotly**.  
- Develop a dashboard to enable deeper insights into the data.  

---

## 📂 **Table of Contents**
1. [Setup](#setup)  
2. [Scenario](#scenario)  
3. [Data Description](#data-description)  
4. [Tasks Overview](#tasks-overview)  
5. [Insights](#insights)  
6. [Next Steps](#next-steps)  

---

## 🚀 **Setup**
### Installing Required Libraries
Use the following command to install the required libraries:
```bash
pip install matplotlib seaborn folium plotly pandas dash
```

### Importing Required Libraries
```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import folium
import plotly.express as px
import dash
```

---

## 🌍 **Scenario**
You have been hired by XYZAutomotives as a data scientist. Your task is to analyze historical automobile sales data and provide insights into how sales were affected during times of recession. Your analysis will help company directors make informed business decisions.  

Recession periods include:
- **1980**  
- **1981–1982**  
- **1991**  
- **2000–2001**  
- **2007–2009**  
- **2020 (COVID-19 Impact)**  

---

## 📊 **Data Description**
The dataset includes the following fields:
- `Date` – Observation date  
- `Recession` – Binary indicator of a recession period (1 = recession, 0 = normal)  
- `Automobile_Sales` – Total vehicle sales during the period  
- `GDP` – Per capita GDP value (USD)  
- `Unemployment_Rate` – Monthly unemployment rate  
- `Consumer_Confidence` – Index representing consumer confidence  
- `Seasonality_Weight` – Seasonal effect on sales  
- `Price` – Average vehicle price  
- `Advertising_Expenditure` – Company's advertising expenditure  
- `Vehicle_Type` – Type of vehicle (e.g., supermini, sports, executive)  
- `Competition` – Market competition level  
- `Month`, `Year` – Date information extracted from `Date`  

---

## ✅ **Tasks Overview**
### **Part 1: Create Visualizations (Matplotlib, Seaborn, Folium)**
- **TASK 1.1:** Develop a line chart to show year-to-year fluctuation in automobile sales.  
- **TASK 1.2:** Plot different lines for vehicle types to analyze sales trends during recessions.  
- **TASK 1.3:** Compare sales trends for recession and non-recession periods using Seaborn.  
- **TASK 1.4:** Use subplots to compare variations in GDP during recession and non-recession periods.  
- **TASK 1.5:** Create a bubble plot to display the impact of seasonality on sales.  
- **TASK 1.6:** Develop a scatter plot to identify the correlation between average vehicle price and sales during recessions.  
- **TASK 1.7:** Create a pie chart to show the portion of advertising expenditure during recessions and non-recessions.  
- **TASK 1.8:** Develop a pie chart to display the total advertising expenditure by vehicle type during recession periods.  
- **TASK 1.9:** Create a line plot to analyze the effect of unemployment rate on vehicle type and sales during recession.  

### **Part 2: Create Dashboard (Plotly, Dash)**
- **TASK 2.1:** Create a Dash application with a meaningful title.  
- **TASK 2.2:** Add dropdown menus to filter data by period and vehicle type.  
- **TASK 2.3:** Add an output display division for dynamic updates.  
- **TASK 2.4:** Create callbacks to update graphs based on user selections.  
- **TASK 2.5:** Create and display graphs for recession report statistics.  
- **TASK 2.6:** Create and display graphs for yearly report statistics.  

---

## 🔎 **Insights**
- Most vehicle types maintained stable sales despite fluctuations in the unemployment rate.  
- Sports and executive cars showed significantly lower and more volatile sales.  
- Medium family cars and small family cars demonstrated the most consistent sales patterns.  
- Advertising expenditure varied between recession and non-recession periods, influencing consumer confidence and sales volume.  

---

## 🚀 **Next Steps**
- Include additional socioeconomic factors in future analysis.  
- Develop a predictive model to forecast vehicle sales based on macroeconomic indicators.  
- Improve the dashboard by adding more interactive elements (e.g., date range selectors).  

---

## 🌐 **Connect With Me**
- **LinkedIn:** [Sam Herd](https://www.linkedin.com/in/samherd)  
- **GitHub:** [SamHerd](https://github.com/SamHerd)  
