# Inventory Management & Sales Analysis using Machine Learning + Power BI

An end-to-end data analytics project focused on **liquor inventory management**, purchase pricing, and sales forecasting. The project uses **Python** for data cleaning, exploratory analysis, and machine learning models, combined with an **interactive Power BI dashboard** for business insights.

---

## 📋 Project Overview

This project analyzes a comprehensive **liquor inventory dataset** (2016–2017) containing purchase prices, beginning/ending inventory, invoices, purchases, and final sales records.

### Key Objectives:
- Clean and preprocess multiple raw CSV files
- Perform Exploratory Data Analysis (EDA)
- Build regression models to predict **Purchase Price** / **Sales Value**
- Create an interactive **Power BI dashboard** for stakeholders to explore inventory trends, sales performance, and pricing insights

**Best Model**: Random Forest Regressor (lowest RMSE after cross-validation)

---

## 🛠️ Technologies Used

- **Python** – Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Power BI** – Interactive dashboards, DAX measures, slicers & filters
- Jupyter Notebook

---

## 📁 Dataset

The project includes **6 CSV files**:

| File Name                        | Description                              |
|----------------------------------|------------------------------------------|
| `2017PurchasePricesDec.csv`      | Product purchase prices & vendor details |
| `BegInvFINAL12312016.csv`        | Beginning inventory (Dec 31, 2016)       |
| `EndInvFINAL12312016.csv`        | Ending inventory (Dec 31, 2016)          |
| `InvoicePurchases12312016.csv`   | Invoice & purchase transactions          |
| `PurchasesFINAL12312016.csv`     | Final purchase records                   |
| `SalesFINAL12312016.csv`         | Final sales records                      |

---

## 📊 Project Workflow

1. **Data Loading** – Import all 6 CSV files
2. **Data Cleaning** – Handle missing values, data type conversion (e.g., Volume column)
3. **Exploratory Data Analysis** – Distribution plots, residual analysis
4. **Feature Engineering** – Pipeline with imputation, scaling, and One-Hot Encoding
5. **Machine Learning Models**:
   - Linear Regression
   - Decision Tree Regressor
   - **Random Forest Regressor** (selected)
6. **Model Evaluation** – RMSE, Cross-validation, Residual plots
7. **Power BI Dashboard** – Interactive visuals for inventory & sales insights

---

## 📈 Results

| Model                | Training RMSE | CV Mean RMSE     | Remarks                  |
|----------------------|---------------|------------------|--------------------------|
| Linear Regression    | -             | -                | Baseline                 |
| Decision Tree        | -             | -                | Prone to overfitting     |
| **Random Forest**    | **Best**      | **Lowest**       | **Final Model**          |

**Power BI Dashboard** includes:
- Sales vs Purchase Price trends
- Inventory turnover analysis
- Vendor performance
- Product-level insights with dynamic filters

*(Screenshots of the dashboard are included in the `images/` folder)*

## 📊 Full Dataset & Dashboard

Due to GitHub file size limitations, large files are stored externally.

🔹 Full Dataset: [[Google Drive Link Here]] 
  1. https://drive.google.com/file/d/1_b8t7wkPxmMffK62ep0iVM9lL8WpNrAu/view?usp=drive_link
  2. https://drive.google.com/file/d/1zgnGR7lJzVaWOZUAUjMJTKtwLa0fZFJl/view?usp=drive_link

🔹 Power BI Dashboard File (.pbix): [Google Drive Link Here] https://drive.google.com/file/d/1PpFs6QcN1SiP3-a8nuVaaTN8ZCYKmlkO/view?usp=drive_link
