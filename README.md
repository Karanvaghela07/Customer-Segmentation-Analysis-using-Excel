<img width="1705" height="699" alt="Screenshot 2025-11-12 231931" src="https://github.com/user-attachments/assets/0db82a03-c450-4f70-b836-40d471e6315d" />




# 🧩 Customer Segmentation Analysis using Excel (RFM Model)

## 📊 Overview
This repository showcases a **Customer Segmentation Analysis** project built entirely in **Microsoft Excel** using the **RFM (Recency, Frequency, Monetary)** model.  
The goal is to analyze customer purchase data, classify customers based on their behavior, and identify actionable insights for business growth.

---

## 🧾 Project Description
The project uses the RFM technique to segment customers into groups such as:
- **High-Value** → Loyal and most profitable customers.
- **Regular** → Consistent buyers with moderate activity.
- **At-Risk** → Customers who have not purchased recently.

This segmentation helps businesses prioritize marketing, improve retention, and target the right customers with the right strategies.

The included Excel file (`Customer_Segmentation_RFM_20Customers.xlsx`) contains:
- ✅ **Raw_Data Sheet** — 80 transactions from 20 unique customers.  
- ✅ **RFM_Analysis Sheet** — automatic calculation of Recency, Frequency, and Monetary values.  
- ✅ **Segmentation Output** — each customer classified into High-Value, Regular, or At-Risk.  
- ✅ **Dashboard-Ready Data** — ideal for creating charts, pivot tables, and Excel dashboards.

---

## 🎯 Objectives
- Perform RFM-based segmentation in Excel.  
- Identify top customers contributing to the majority of revenue.  
- Provide data-driven recommendations to improve customer retention.  
- Visualize segment distribution and revenue contribution.

---

## 📂 Dataset Structure
| Column Name | Description |
|--------------|--------------|
| CustomerID | Unique identifier for each customer |
| InvoiceDate | Date of purchase |
| InvoiceNo | Invoice number for the transaction |
| Amount | Purchase amount (in INR or USD) |

---

## ⚙️ Methodology
1. **Data Cleaning** – Removed duplicates and missing values.  
2. **RFM Calculation** – Used Excel formulas:  
   - `Recency = TODAY() - MAX(InvoiceDate)`  
   - `Frequency = COUNT(InvoiceNo)`  
   - `Monetary = SUM(Amount)`  
3. **Scoring** – Each metric scored from 1–5 using Excel’s `QUARTILE()` function.  
4. **Segmentation** – Combined RFM scores to form groups (e.g., 555 → High Value).  
5. **Visualization** – Used Pivot Tables and conditional formatting for insights.

---

## 💡 Insights & Recommendations
- Top 20% of customers contribute ~80% of revenue.  
- Regular customers can be converted into high-value with loyalty programs.  
- At-risk customers should receive personalized reactivation offers.  
- Monitoring **Recency** helps detect potential churn early.

---

## 📈 Tools Used
- Microsoft Excel  
- Pivot Tables  
- Conditional Formatting  
- Data Cleaning & Formulas  
- RFM Model (Segmentation Framework)

---

## 🧠 Business Benefits
- Enables data-driven marketing and retention strategies.  
- Helps businesses identify and reward loyal customers.  
- Improves targeting efficiency and reduces churn risk.  
- Provides a foundation for automation or Power BI integration.

---

## 🚀 How to Use
1. Download the Excel file: `Customer_Segmentation_RFM_20Customers.xlsx`.  
2. Open it in Microsoft Excel or Google Sheets.  
3. Review both sheets: `Raw_Data` and `RFM_Analysis`.  
4. Insert Pivot Tables and Charts for custom dashboards.  
5. Modify or expand the dataset for your own business needs.

---

## 🧩 Future Enhancements
- Add an **interactive Excel Dashboard** with slicers and charts.  
- Automate RFM scoring using **Excel VBA macros**.  
- Integrate with **Power BI** for advanced visualization.  
- Apply the RFM model to **real-world retail or e-commerce data**.

---

## 👨‍💻 Author
**Karan Vaghela**  
Data Analytics & AI Enthusiast  
📅 November 2025  

---

## 🏷️ Tags
`Excel Analytics` • `Customer Segmentation` • `RFM Model` • `Data Visualization` • `Business Insights`
