from pathlib import Path

# Define the README content
readme_content = """\
# 💼 Power BI Sales Report Dashboard

This project is based on Microsoft’s official Power BI tutorial: **"From Excel workbook to stunning report in Power BI Desktop."** It demonstrates the end-to-end process of importing, transforming, analyzing, and visualizing financial data in Power BI.

## 📊 Project Overview

- **Objective:** Build an interactive and insightful sales report dashboard using sample financial data.
- **Tools Used:** Power BI Desktop
- **Skills Demonstrated:**
  - Data Transformation (Power Query)
  - Data Modeling
  - DAX Measures and Calculations
  - Report Design and Layout
  - Visual Interactions with Slicers

## 📁 Dataset

The dataset is provided by Microsoft and contains sample financial data:
- Product Category & Subcategory
- Sales, Profit, and Discount
- Geographic Location
- Time Periods (Date Hierarchies)

## 🛠️ Key Features

| Feature                 | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| 📈 Line Chart           | Visualizes sales trends over time                                           |
| 🗺️ Map Visualization    | Shows geographic sales distribution                                         |
| 📊 Bar Charts           | Highlights profit by product category                                       |
| 🎛️ Slicers              | Enables filtering by region, product, and time period                       |
| 📐 DAX Measures         | Custom calculations like Total Sales, Profit Margin, and Discount Percentage|

## 🧠 Learnings

- How to clean and prepare messy data with Power Query
- Creating calculated columns and measures using DAX
- Best practices in dashboard design and user experience
- Adding interactivity using slicers and drill-throughs

## 📸 Screenshots

> Include 1–2 screenshots of your report pages here (if applicable).

## 🔗 Resources

- [Official Microsoft Tutorial](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download)

## 🚀 How to Use

1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Open the `.pbix` file provided in this repo
3. Explore, interact, and customize the report visuals

## 📥 Files Included

- `Financial Sample.xlsx` – Excel data source
- `Sales_Report.pbix` – Power BI report file
- `README.md` – Project documentation

## 📌 Author

- **Kamesh V**
- GitHub: [@kamesh63](https://github.com/kamesh63)
- LinkedIn: [V Kamesh](https://www.linkedin.com/in/v-kamesh-0ab95b251/)
"""

# Save the README file
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content)

readme_path

