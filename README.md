# 🚗 BMW Global Sales Analysis and Performance Insights (2018–2025)

**Tools & Technologies:** Power BI | Excel | Power Query | DAX | Data Modeling  
**Domain:** Sales Analytics | Automotive  

---

## 🧩 Project Overview

This project analyzes BMW’s global sales performance from **2018 to 2025**, focusing on vehicle sales, revenue generation, regional performance, product distribution, and electric vehicle (EV) adoption.

The dataset was sourced from **Kaggle** and processed using **Excel and Power Query**. A structured **star schema data model** was implemented in Power BI, enabling efficient analysis and interactive dashboard development.

Additionally, the analysis integrates **economic indicators (GDP growth and fuel price index)** to evaluate external factors influencing automotive sales performance.

---

## 🎯 Project Objectives

- Analyze **monthly and yearly sales trends** to identify seasonal patterns  
- Evaluate **regional revenue contribution** across key markets  
- Assess **model-wise performance** and product distribution  
- Analyze **EV segment performance and contribution to total sales**  
- Examine the **impact of economic indicators (GDP growth, fuel price index)**  
- Enable **data-driven strategic decision-making**  

---

## 📁 Data Source

- **Dataset:** BMW Global Sales Dataset (Kaggle)  
- **Time Period:** 2018–2025  
- **Processing Tools:** Excel, Power Query  
- **Visualization Tool:** Power BI  

---

## ❓ Problem Statement

- Which regions generate the highest revenue?  
- Which BMW models contribute most to total sales?  
- Do sales follow seasonal patterns?  
- How competitive is the EV segment?  
- How do economic conditions influence vehicle sales?  
- What is the EV contribution to total market share?  

---

## 🧾 Dataset Attributes

| Attribute Name | Data Type | Description |
|---|---|---|
| Year | Integer | Sales year |
| Month | Integer | Month number |
| Month Name | Text | Month name |
| Region | Text | Sales region |
| Model | Text | Vehicle model |
| Units_Sold | Whole Number | Total vehicles sold |
| Revenue_EUR | Currency | Revenue generated |
| EV_Sales | Whole Number | Electric vehicle sales |
| GDP_Growth | Decimal | Economic indicator |
| Fuel_Price_Index | Decimal | Fuel trend indicator |
| Avg_Price_EUR | Currency | Average vehicle price |
| BEV_Share | Decimal | EV share |
| Premium_Share | Decimal | Premium segment contribution |

---

## 🧹 Data Preprocessing

### Data Cleaning (Power Query)
- Removed duplicate records  
- Handled missing values  
- Standardized column formats  

### Data Transformation
- Created calculated fields (Avg_Price_EUR, BEV_Share, Premium_Share)  
- Derived EV-related indicators  

### Data Modeling
- Implemented **Star Schema**  
- Fact Table: Sales Data  
- Dimension Tables: Year, Month, Region, Model  

---

## 🧮 DAX Measures

- **Total Vehicles Sold** = SUM(Units_Sold)  
- **Total Revenue** = SUM(Revenue_EUR)  
- **Average Vehicle Price** = DIVIDE([Total Revenue], [Total Vehicles Sold])  
- **EV Contribution %** = DIVIDE(SUM(EV_Sales), SUM(Units_Sold))  

---

## 📊 Analysis & Visualizations

An interactive **Power BI dashboard** was developed with:

- 📈 **Line Chart:** Monthly & Yearly Sales Trend  
- 📊 **Bar Chart:** Model-wise Sales Performance  
- 📉 **Column Chart:** Regional Revenue Comparison  
- 🍩 **Donut Chart:** EV Market Share Distribution  
- 📊 **Dual-Axis Chart:** GDP Growth vs Revenue Trend  
- 📌 **KPI Cards:** Key performance indicators  

---

## 📈 Key Performance Metrics

- **Total Vehicles Sold:** 24.52 Million  
- **Total Revenue:** €1.57 Trillion  
- **Average Vehicle Price:** €45.04K  
- **EV Contribution:** 11.1%  

---

## 🔍 Key Insights

- China is the **highest revenue-generating region**  
- Sales exhibit **seasonal variation across months**  
- BMW maintains **balanced model sales distribution**  
- EV models show **competitive market share**, with **iX slightly leading**  
- EV contribution is **11.1%**, indicating **early-stage adoption**  
- **GDP growth influences revenue trends**, showing economic impact  

---

## 🏁 Conclusion

This project demonstrates how **data analytics and visualization techniques** can provide actionable insights into automotive sales performance.

### Final Takeaways

- Revenue is **regionally concentrated**, with China leading  
- Sales follow **consistent seasonal demand patterns**  
- Product portfolio is **well-balanced across models**  
- EV adoption is **growing but still in early stages**  
- **Economic indicators significantly impact sales performance**  

---

## 👨‍💻 Author

**Nitesh Raj R G**  
Aspiring Data Analyst  

- 🌐 GitHub: https://github.com/rgniteshraj  
- 💼 LinkedIn: https://www.linkedin.com/in/niteshrajrg  
- 📧 Email: rgniteshraj@gmail.com  
