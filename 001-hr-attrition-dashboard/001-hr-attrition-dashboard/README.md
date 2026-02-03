# 📄 Understanding Power BI File Formats: .pbix vs .pbit

When working with Power BI, it is essential to understand the difference between a **Report (.pbix)** and a **Template (.pbit)**. This guide explains their unique roles in data sharing and version control.

---

## 🏗️ 1. .pbix (Power BI Report)
The **.pbix** file is the standard working file for Power BI. It is a "complete package."

- **What it contains:** It includes the report metadata (visuals, layout, and DAX) **AND** the actual data imported from your source.
- **File Size:** Usually large, as it stores all the rows of data from your CSV/Database.
- **Best Use Case:** - Daily development and analysis.
    - Publishing to the Power BI Service.
    - Sharing a "ready-to-view" report where the recipient doesn't need to refresh data.
- **Security:** Since the data is inside the file, anyone with the file can see the numbers.

---

## 📐 2. .pbit (Power BI Template)
The **.pbit** file is a "blueprint" or a skeleton of your report.

- **What it contains:** It includes the report metadata (visuals, layout, and DAX) but **DOES NOT** contain the actual data.
- **File Size:** Extremely small (often just a few kilobytes).
- **Best Use Case:** - Sharing your dashboard structure without sharing sensitive data.
    - Creating a reusable layout for different departments.
    - Version control (GitHub/GitLab) because the file size is manageable.
- **Security:** When a user opens a `.pbit`, Power BI prompts them to provide credentials or a file path to load the data fresh.

---

## 📊 Comparison Summary

| Feature | .pbix (Report) | .pbit (Template) |
| :--- | :--- | :--- |
| **Data Storage** | Included (Cached in file) | None (Metadata only) |
| **File Size** | Large | Very Small |
| **Privacy** | High risk (Data is visible) | Lower risk (Requires data access) |
| **On Open** | Opens immediately | Prompts for Data/Parameters |
| **Ideal For** | Final Presentation | Sharing Structure / Templates |

---

## 🚀 How to use these in this project:
1. **Use the .pbix** if you want to see the **HR Analytics** results immediately with the pre-loaded data.
2. **Use the .pbit** if you want to apply this specific **HR Dashboard layout** to your own custom dataset (ensuring your CSV columns match the original structure).

