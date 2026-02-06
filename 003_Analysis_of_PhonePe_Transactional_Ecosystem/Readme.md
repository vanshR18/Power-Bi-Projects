# 📱 PhonePe Pulse Data Analysis Dashboard

## 📌 Introduction
This project provides a comprehensive data-driven analysis of **PhonePe** transaction trends, user demographics, and payment success metrics for the year 2024. The dashboard is designed to help stakeholders visualize transaction volumes, identify common payment failure points, and understand user behavior across various financial services.

---

## 🎯 Business Objectives
The primary goal of this dashboard is to provide actionable insights into the digital payment ecosystem:
* **Transaction Monitoring:** Track total successful vs. failed transactions and overall revenue.
* [cite_start]**Service Performance:** Analyze the performance of different segments such as Loans, Insurance, Money Transfers, and Bill Recharges[cite: 422].
* [cite_start]**Failure Analysis:** Identify the root causes of transaction failures to improve payment success rates[cite: 450, 453].
* [cite_start]**User Demographics:** Understand the age distribution and growth of the user base[cite: 488, 493].

---

## 📈 Key Metrics (KPIs)
* [cite_start]**Total Amount Processed:** ₹3,474M [cite: 413, 414]
* [cite_start]**Total Transactions:** 300K [cite: 415]
* [cite_start]**Total Successful Transactions:** 3,333M [cite: 409, 410]
* [cite_start]**Total Failed Transactions:** 141M [cite: 407, 408]
* [cite_start]**Average User Age:** 39 years [cite: 489, 493]

---

## 📊 Visualizations & Insights
The dashboard consists of multiple pages focusing on different business units:

1. **Overall Performance:**
   * [cite_start]**Date vs. Amount:** A line chart showing monthly revenue peaks, with a significant high in July (₹13.70M)[cite: 456, 457, 464].
   * [cite_start]**Failed Payment Reasons:** A pie chart highlighting that **Server Errors (33.76%)** and **Wrong PINs (27.61%)** are the leading causes of failed transactions[cite: 450, 452, 454, 466, 468].

2. **User Insights:**
   * [cite_start]**User Joined by Month:** Tracking new user acquisition trends throughout the year[cite: 487].
   * [cite_start]**User vs. Age:** Bar chart showing the majority of the user base is concentrated between ages 20 and 50[cite: 488, 490, 491, 492].

3. **Service Breakdown:**
   * [cite_start]**Insurance & Loans:** Detailed analysis of total transactions and failed amounts for specific categories like Bike, Car, and Health insurance[cite: 545, 546, 550, 555].
   * [cite_start]**Money Transfers:** Performance metrics for UPI ID, QR Code, and Mobile Number transfers[cite: 689, 697, 700].
   * [cite_start]**Recharges & Bills:** Analysis of Mobile Recharges, Electricity, DTH, and Cable TV payments[cite: 758, 764, 776, 780].

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
