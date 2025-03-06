# 📊 Customer Analytics Dashboard (Power BI)  

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

---

## 📊 Power BI Customer Analytics Dashboard  

📌 **Live Dashboard Link**: [View Dashboard](https://app.powerbi.com/reportEmbed?reportId=YOUR_REPORT_ID)  

### **Dashboard Features:**  
✅ **Customer Segmentation View** – RFM-based classification of customers.  
✅ **Sales Performance Analysis** – Revenue trends, product demand, and sales distribution.  
✅ **Customer Retention Insights** – Identifying at-risk and lost customers.  
✅ **RFM Score Breakdown** – Interactive visual analysis of customer behavior.  

![Customer Analytics Dashboard](https://github.com/yourusername/customer-analytics/blob/main/dashboard_screenshot.png)  

---

## 🛠️ Tools & Technologies Used  
✔ **Power BI** - Data cleaning (Power Query), modeling, and visualization  
✔ **DAX (Data Analysis Expressions)** - Calculated measures for RFM scores  
✔ **Excel** - Initial dataset inspection and preprocessing  

---

## 📈 Key Insights from Analysis  
✅ **High-value customers contribute a significant portion of total revenue.**  
✅ **Customers who purchase frequently tend to spend more over time.**  
✅ **A large segment of customers have not made recent purchases, indicating potential churn.**  
✅ **Targeted promotions for high RFM-score customers can drive repeat purchases.**  

---

## 🚀 How to Use This Project  

### **1️⃣ Download the Power BI Report**  
- Download the `.pbix` file from the repository.  
- Open it using **Power BI Desktop**.  

### **2️⃣ Connect to the Dataset**  
- The dataset is available in `.csv` format inside the `/data` folder.  
- Load it into Power BI for further exploration.  

### **3️⃣ Explore the Interactive Dashboard**  
- Use slicers to **filter customers by RFM scores, sales trends, and spending patterns**.  
- Hover over visuals to **view detailed customer insights**.  

---

## 🏆 Contribution Guidelines
🔹 If you find this project useful, **star** ⭐ the repository!  
🔹 Fork the repository and submit a **pull request** for improvements.  
🔹 Found an issue? **Open a discussion or issue** to suggest enhancements.  

---

## 📌 About Me
Hi, I'm Oluwatosin Amosu Bolaji, a Data Analyst skilled in SQL, Power BI, and Excel. I enjoy turning complex datasets into actionable insights through data visualization and business intelligence techniques.

- **🔹 Key Skills:** Data Analysis | SQL Queries | Power BI Dashboards | Data Cleaning | Reporting
- **🔹 Passionate About:** Data storytelling, problem-solving, and continuous learning

## 📬 Contact & Connect
- **📩 Email**: your-email@example.com  
- **💼 LinkedIn**: [linkedin.com/in/yourprofile](#)  
- **🐦 Twitter/X**: [@yourhandle](#)  
- **🌍 Portfolio**: [your-portfolio-link.com](#)  

---
📌 **If you found this project useful, please give it a ⭐!**  

