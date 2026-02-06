# 📱 PhonePe Data Analysis Dashboard

## 📌 Introduction
This project provides a comprehensive data-driven analysis of **PhonePe** transaction trends, user demographics, and payment success metrics for the year 2024. The dashboard is designed to help stakeholders visualize transaction volumes, identify common payment failure points, and understand user behavior across various financial services.

---

## 🎯 Business Requirement & Objectives
The primary objective of this dashboard is to provide a detailed analysis of the PhonePe ecosystem to identify transaction patterns and technical bottlenecks.

* **Transaction Monitoring:** Track total successful vs. failed transactions and overall revenue volumes.
* **Service Performance:** Analyze the efficiency of different segments like Loans, Insurance, and Bill Recharges.
* **Failure Analysis:** Identify root causes of transaction failures to suggest improvements for payment success rates.
* **User Demographics:** Explore user age distribution and acquisition trends.

---

## 📈 Key Performance Indicators (KPIs)
* **Total Amount:** ₹3,474M — The overall value processed across the platform.
* **Total Transactions:** 300K — The total count of transaction attempts.
* **Successful Transactions:** 3,333M — Total count of completed payments.
* **Failed Transactions:** 141M — Total count of unsuccessful payments.
* **Average User Age:** 39 Years — The mean age of the active user base.

---

## 📊 Dashboard Structure
The Power BI dashboard consists of **five interactive pages**:

1. **🏠 Home Page – Overall Summary**
   * High-level overview of total transactions, amounts, and failed payments.
   * Date range slicers for global filtering across the report.

2. **❌ Failed Transactions Analysis**
   * Detailed breakdown of failed transactions and their root causes (e.g., server error, wrong PIN).
   * Trend analysis showing how failures fluctuate by month.

3. **🛡️ Insurance Dashboard**
   * Analysis specifically for Bike, Car, Health, and Term Life insurance categories.
   * Successful vs. failed payment comparison within the insurance sector.

4. **💰 Loan Dashboard**
   * Tracking loan transaction trends and payment status comparisons.
   * Reusable design structure for consistent reporting across different loan types.

5. **💳 Recharges, Bills & Money Transfers**
   * Detailed analysis of Mobile Recharges, Electricity, and DTH payments.
   * Money transfer performance via UPI ID, QR Code, and Mobile Number.

---

## 📊 Visualizations & Insights
* **Failed Payment Reasons:** **Server Errors (33.76%)** and **Wrong PINs (27.61%)** are the leading causes of failures.
* **Monthly Trends:** Monthly revenue reached a significant high of **₹13.70M in July**.
* **Demographics:** The majority of the user base is concentrated between **ages 20 and 50**.
* **Service Breakdown:** Loans represent the largest segment by amount (**₹2.5bn**), followed by Insurance (**₹0.5bn**).

---
---

## 🛠️ Technologies Used
* **Power BI:** For creating the multi-page interactive dashboard.
* **Data Modeling:** To establish relationships between transaction and user datasets.
* **DAX (Data Analysis Expressions):** For calculating complex measures like transaction success rates and average user age.

---
## 📂 Project Structure
```text
003_PhonePe-Pulse-Analysis/
├── Data/
│   ├── PhonePe_Transaction_Data.xlsx         # Raw Dataset
│   └── PhonePe_Analysis_Problem_Statement.pdf # Problem Statement
└── Reports/
    ├── PhonePe_Analysis_Report.pbix          # Power BI Report
    ├── PhonePe_Analysis_Report.pdf           # Static PDF Export
    └── Readme.md
```

---

## 🚀 How to Use
1. **Download** the `.pbix` file from the `Reports/` folder.
2. **Open** in **Power BI Desktop**.
3. **Use the Date Range Slicers** at the top to filter data for specific months or quarters.
4. **Navigate** through the side icons to switch between **Insurance, Loans, and Money Transfer** views for deeper analysis.

---

## ✅ Outcomes
The PhonePe Dashboard serves as a valuable tool for data-driven decision-making. It empowers stakeholders to:
* **Identify technical failure points:** pinpoints specific issues like Server Errors to improve platform stability.
* **Optimize marketing strategies:** targets the core 20–50 age demographic which forms the bulk of the user base.
* **Monitor high-volume services:** tracks the growth of UPI ID and Mobile Number transfers to prioritize feature updates.

---

## 📬 Feedback & Contact
I am passionate about Data Science, Data Analytics, and Visualization.  
Feel free to reach out on **LinkedIn** for any discussions or feedback!

---

## 🔖 Tags
Power BI | Fintech Analytics | Transaction Dashboard | Data Visualization | DAX | Business Intelligence

---
*Developed by Rohit Pal*
