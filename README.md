# 🏎️ Lamborghini Business Insights Dashboard – Power BI & Snowflake

A **data-driven business intelligence project** built using **Power BI** and **Snowflake**, featuring a fully synthetic yet realistic dataset modeled after Lamborghini’s operations.  
The project provides deep insights into **sales performance, customer behavior, dealer efficiency, EV adoption, and marketing effectiveness** through an interactive, multi-page Power BI dashboard.

---

## 📂 Project Overview

This project simulates a real-world **automotive business analytics solution** using a **synthetic dataset** of over:

- 🚘 **80,000+ vehicle sales**
- 👥 **5,000+ customers**
- 🏢 **150+ dealers**
- 📈 **Multiple marketing campaigns**

It aims to replicate how a premium brand like **Lamborghini** might analyze performance, sales, and market dynamics using modern BI tools.

---

## 🧠 Tools & Technologies Used

- **Power BI** – Data visualization & DAX measures  
- **Snowflake** – Cloud data warehouse for advanced SQL querying *(used in Part 2)*  
- **Excel / Python (Synthetic Data Generation)** – For realistic dataset creation  
- **GitHub** – Project hosting & version control  

---

## 🚀 Dashboard Pages Overview

### 🏁 Executive Summary
![Executive Summary](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Executive%20Summary.png)

Key KPIs and business overview:  
- Total Profit: **$45.3B (+31.4% YoY)**  
- Total Sales: **$48.6B**  
- Units Sold: **81K (+31.9%)**  
- Profit Margin: **93.8%**  
- EV Sales Growth: **31%**

Features: Dynamic DAX parameters, year-over-year comparisons, and shapemap-based regional insights.

---

### 🏎️ Model Insights
![Model Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Model%20Insights.png)

Gain insights into:
- Profitability by **model and body type**
- Top-performing models like *Countach LP800* and *Sian*
- Average selling price, transmission, and horsepower
- Best-performing regions, dealers, and customer segments

---

### 🏢 Dealer Insights
![Dealer Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Dealer%20Insights.png)

Metrics include:
- **Top dealer**: Elite Motors ($4.48B profit)
- **Average dealer rating**: 4.2 ⭐  
- **Service center availability**: 53%
- **Dealer commission paid**: $1.94B  

Includes scatter plots, sparkline tables, and top/bottom dealer comparisons.

---

### 🔍 Individual Dealer Insights
![Individual Dealer Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Individual%20Dealer%20Insights.png)

A drillthrough page showing:
- Dealer-specific sales, units, and performance
- EV vs Non-EV breakdown  
- Top 5 customers by sales  
- Profit trends over time  
- Actual vs Target sales gauge  

---

### ⚡ EV Insights
![EV Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/EV%20Insights.png)

Focuses on the growing **Electric Vehicle (EV)** market:
- Total EV Sales: **$20B (+31% YoY)**
- Top regions: **Asia & Europe**
- Leading EV: *Reventón Base (3K units sold)*
- Age and customer trends for EV buyers
- Regional and dealer-level EV adoption

---

### 🧍 Customer Insights
![Customer Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Customer%20Insights.png)

Understand your customer base:
- **Total Customers:** 5,000  
- **Repeat Buyers:** 17.4%  
- **Avg CLV:** $207K  
- **Avg Satisfaction Score:** 3.9 / 5  
- **Top Occupation:** Investors  
- Segmentation by VIP status, type, and income group

---

### 📢 Marketing Campaign Insights
![Marketing Campaign Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Marketing%20Campaign%20Insights.png)

Analyze campaign effectiveness and ROI:
- **Top Campaign:** Legends Gala (Revenue $4.78M)  
- **Best Campaign Type:** Awareness (Avg ROI 95%)  
- **Average ROI:** 91.48%  
- **EV-focused ROI:** 138%  
- Includes decomposition tree and scatter chart for spend vs. ROI  

---

### 🎯 Individual Campaign Insights
![Individual Campaign Insights](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Individual%20Campaign%20Insights.png)

Campaign-specific deep dive:
- Cards for **campaign name, ROI, EV focus, influencer usage, spend, and duration**
- Visuals:
  - Shapemap: Purchases by Country  
  - Bar & Column Charts: Region and Model Performance  
  - Donut Charts: EV vs Non-EV, Customer & Dealer Segments  
  - Breakdown by **Sales Channel** and **Campaign Focus**

---

### 🏠 Home Page
![Home Page](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Home%20Page.png)

A **clean, interactive homepage** designed using **Power BI bookmarks** for smooth navigation across pages.

---

### 🧩 Relational Model
![Relational Model](https://github.com/divyamehulmakwana-bit/Lamborghini-Dashboard-using-PowerBi-and-Snowflake/blob/main/Screenshots/Model.png)

Structured with a **central fact table (Sales)** connected to dimension tables:
- Vehicles  
- Customers  
- Dealers  
- Marketing Campaigns  
- Vehicle Image URLs  

Ensures a robust star-schema design for efficient analytics.

---

## 🧮 Dataset Information

The **Lamborghini Synthetic Dataset** was generated using **ChatGPT** to simulate realistic business conditions.  
It includes detailed attributes such as:
- Vehicle specs (engine, drivetrain, horsepower, category, etc.)
- Sales transactions (price, discount, tax, commission)
- Customer details (demographics, CLV, satisfaction index)
- Dealer info (type, rating, region)
- Marketing campaigns (spend, ROI, EV focus, influencer usage)

📌 Note: *This dataset is entirely synthetic and created for educational & portfolio purposes only.*

---

## 🧊 Part 2 – Snowflake Integration (Coming Soon)

The next phase of this project will focus on:
- Uploading the dataset into **Snowflake**
- Running **SQL queries** for deeper insights
- Integrating results back into Power BI  
Stay tuned for **Part 2** of the project!

---

## 📬 Contact

📧 **Email:** divyamehulmakwana@gmail.com  
💼 **LinkedIn:** [Divya Makwana](https://www.linkedin.com/in/divya-makwana-2929b4378/)  

I’m currently **open to work** and always open to **collaborations** in the fields of  
**Data Analytics, Business Intelligence, and Visualization**.

If you found this project interesting, feel free to ⭐ **star the repo** or connect with me!

---

## 🏷️ Keywords

`Power BI` • `Data Analytics` • `Dashboard Design` • `Snowflake` • `Business Intelligence`  
`Synthetic Data` • `Automotive Analytics` • `Data Visualization` • `DAX` • `SQL` • `Open To Work`

---

⭐ **If you like this project, don’t forget to star the repository!**
