# 📊 Customer RFM Analytics Dashboard Analysis (Using Power BI)  

![Screenshot (85)](https://github.com/user-attachments/assets/b8746cc2-fec5-4f6e-9c7c-48b234f8bcda)


## 📌 Project Overview  
This project focuses on **Customer Analytics using RFM (Recency, Frequency, Monetary) Analysis** to segment customers based on their purchasing behavior. By leveraging **Power BI’s data visualization and analytics capabilities**, the dashboard provides actionable insights to improve **sales strategies and customer retention**.

Using **Power BI**, this project:  
- **Segments customers** based on their purchase behavior using **RFM analysis**.  
- **Identifies high-value customers** for targeted marketing campaigns.  
- **Analyzes sales performance** to optimize business decisions.  
- **Visualizes key sales insights** through an interactive Power BI dashboard.  

---

## 🎯 Business Problem  

### **🔎 Problem Statement**  
Understanding **customer behavior** is crucial for businesses aiming to improve **sales performance and customer loyalty**. Without proper customer segmentation, marketing efforts may be inefficient, leading to **lost revenue opportunities**.  

This project answers key business questions:  
- **Who are the most valuable customers based on their purchasing behavior?**  
- **How frequently do customers make purchases, and how recently did they buy?**  
- **Which customer segments contribute the most to revenue?**  
- **How can businesses optimize marketing strategies based on customer segmentation?**

---

## 🛠️ Tools & Technologies Used  
✔ **Power BI** - Data cleaning (Power Query), modeling, and visualization  
✔ **DAX (Data Analysis Expressions)** - Calculated measures for RFM scores  
✔ **Excel** - Initial dataset inspection and preprocessing 
- ![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-F2C811?logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power_Query-F2C811?logo=powerbi&logoColor=black)


---

## 📊 Dataset Information  
The dataset consists of **customer transaction records** with details on purchase history and spending patterns.  

| Table Name         | Description |
|---------------------|-------------|
| `Customer`      |Contains Details for each customer |
| `Geography` | Contains Location Of Each Customer |
| `Product`       | Unique identifier for each product|
| `Sales Territory` | Category of the purchased product |
| `Internet Sales`     | Fact Table for each transaction details |
| `RFM Description` | Customer segmentation Description |
| `RFM Segments` | Customer segmentation |

---

## 🔎 **RFM Analysis Explanation**  
RFM (Recency, Frequency, Monetary) analysis is used to segment customers based on:  

- **Recency (R)** – How recently a customer made a purchase.  
- **Frequency (F)** – How often a customer makes a purchase.  
- **Monetary (M)** – How much revenue a customer generates.  

Using Power BI, we assign **RFM scores** to categorize customers into:  
✅ **High-Value Customers** (Frequent, recent, and high spenders)  
✅ **Potential Loyalists** (Frequent shoppers but lower spending)  
✅ **At-Risk Customers** (Long time since last purchase, high spenders)  
✅ **Lost Customers** (No purchases in a long period)  

---

## ⚡ Power BI Data Processing & Cleaning (Power Query)  

### **1️⃣ Data Cleaning & Preprocessing**  
✔ **Removed duplicate transactions** to ensure data integrity.  
✔ **Converted `Transaction_Date` to Date format** for time-based analysis.  
✔ **Handled missing values** in purchase data.  
✔ **Created new calculated columns** for RFM scoring.  

### **2️⃣ Data Transformation & Modeling**  
✔ **Established relationships** between transaction and customer data.  
✔ **Created DAX measures** for RFM calculations.  
✔ **Generated segmentation groups** using RFM scores. 

![Screenshot (84)](https://github.com/user-attachments/assets/f280602d-3ad0-4c76-9b9f-753b88645109)
- *Image Showing Completed Data Model*

---

## 📊 Power BI Customer Analytics Dashboard 

### Dashboard Overview:
![Screenshot (85)](https://github.com/user-attachments/assets/8a2bbf3e-18c7-41fd-9b47-837844346bb3)

### Customer Segmentation Analysis:
![Screenshot (86)](https://github.com/user-attachments/assets/4e0ee34d-08c1-4a56-b104-279909624f47)

### Customer Details:
![Screenshot (116)](https://github.com/user-attachments/assets/fc78f0a5-d5ea-4026-94d5-dffbbc296ee5)


### Explore the Interactive Dashboard 
- Use slicers to **filter customers by RFM scores, sales trends, and spending patterns**.  
- Hover over visuals to **view detailed customer insights**.  

📌 **Live Dashboard Link**: Click to [View Live Interactive Dashboard](https://app.powerbi.com/reportEmbed?reportId=YOUR_REPORT_ID) 

### **Dashboard Features:**  
✅ **Customer Segmentation View** – RFM-based classification of customers.  
✅ **Sales Performance Analysis** – Revenue trends, product demand, and sales distribution.  
✅ **Customer Retention Insights** – Identifying at-risk and lost customers.  
✅ **RFM Score Breakdown** – Interactive visual analysis of customer behavior.  

---

## 📈 Key Insights from Analysis  
✅ **High-value customers contribute a significant portion of total revenue.**  
✅ **Customers who purchase frequently tend to spend more over time.**  
✅ **A large segment of customers have not made recent purchases, indicating potential churn.**  
✅ **Targeted promotions for high RFM-score customers can drive repeat purchases.**  

---

## 🏆 Contribution Guidelines
🔹 If you find this project useful, **star** ⭐ the repository!  
🔹 Fork the repository and submit a **pull request** for improvements.  
🔹 Found an issue? **Open a discussion or issue** to suggest enhancements.  

---

## 📌 About Me
Hi, I'm Oluwatosin Amosu Bolaji, a Data Analyst with strong skills in Python, SQL, Power BI, and Excel. I turn raw data into actionable insights through automation, data storytelling, and visual analytics.

- **💡 Tools & Tech:** **Python** (Pandas, NumPy, Matplotlib, Seaborn) | **SQL** (MsSQL, Postgree, MySQL) | **Microsoft Power BI** | **Microsoft Excel**
- **🔹 Key Skills:** Data wrangling, dashboarding, reporting, and process optimization.
- ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-2.0.0-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-1.21.0-013243?logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.0-blue?logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-0.11.0-black?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-5.5.0-3F4F75?logo=plotly)
- ![SQL](https://img.shields.io/badge/SQL-Server-red?logo=microsoft-sql-server&logoColor=white) ![MS SQL](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?logo=microsoft-sql-server&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
- ![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-F2C811?logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power_Query-F2C811?logo=powerbi&logoColor=black)
- ![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white)

#### 🚀 **Always learning. Always building. Data-driven to the core.**  

### 📫 **Let’s connect!**  
- 📩 oluwabolaji60@gmail.com
- 🔗 : [LinkedIn](https://www.linkedin.com/in/oluwatosin-amosu-722b88141)
- 🌐 : [My Portfolio](https://www.datascienceportfol.io/oluwabolaji60) 
- 𝕏 : [Twitter/X](https://x.com/thee_oluwatosin?s=21&t=EqoeQVdQd038wlSUzAtQzw)
- 🔗 : [Medium](https://medium.com/@oluwabolaji60)
- 🔗 : [View my Repositories](https://github.com/Tbrown1998?tab=repositories)

---
📌 **If you found this project useful, please give it a ⭐!**  

