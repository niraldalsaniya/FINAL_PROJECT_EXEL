Here is a proper, step-by-step README file for your Excel Sales Dashboard project. You can copy it into a separate sheet named Read Me in the same Excel workbook.

# README — Excel Sales Dashboard Project

📊 Retail Sales Analysis & Interactive Dashboard

# 📊 Retail Sales Analysis & Interactive Dashboard

## 1. Project Introduction

This project uses Microsoft Excel to analyze retail sales data and create an interactive dashboard. It helps users understand sales performance, product performance, monthly trends, and country-wise sales.

## 2. Project Objectives

* Import and organize the dataset.

* Clean missing and duplicate data.

* Calculate total sales using Excel formulas.

* Create summary tables for sales analysis.

* Use advanced Excel formulas.

* Create charts and graphs.

* Build an interactive dashboard with filters.

* Present results in a simple and understandable way.

## 3. Workbook Sheets

### Sheet 1: Read Me

Contains project information, instructions, chart descriptions, and explanations of all workbook sheets.

### Sheet 2: Raw Data

Stores the original retail dataset. This sheet preserves the imported records for reference.

### Sheet 3: Cleaned Data

Contains prepared data for analysis. Duplicate records and rows with missing values are removed. Additional columns are used to calculate total sales, month, and year.

**Total Sales Formula:**
`=Quantity*UnitPrice`

### Sheet 4: Pivot Analysis

Contains summary tables used to compare sales by country, identify top-selling products, and review monthly sales.

### Sheet 5: Advanced Formulas

Demonstrates Excel functions such as:

* SUM — calculates total sales.

* AVERAGE — calculates average unit price.

* COUNTA — counts records.

* COUNTIF — counts records that meet a condition.

* IF — returns results based on a condition.

* VLOOKUP — searches for a value in a table.

* INDEX and MATCH — find matching information in a summary table.

### Sheet 6: Visualizations

Contains charts that present sales information visually and make comparisons easier.

### Sheet 7: Dashboard

Displays important sales figures and charts in one place. The dashboard includes country and month dropdown filters, KPI cards, and charts for quick analysis.

## 4. Step-by-Step Project Workflow

### Step 1: Import the Dataset

Open the Raw Data sheet and review the original retail transaction records.

### Step 2: Clean the Data

Open the Cleaned Data sheet. Remove duplicate rows, handle missing values, and check that dates and numeric values use the correct formats.

### Step 3: Calculate Total Sales

Calculate sales for each transaction line by multiplying quantity by unit price.

Formula: `=D2*F2`

Copy the formula down for all records.

### Step 4: Create Summary Tables

Use the Pivot Analysis sheet to summarize sales by country, product, and month. These summaries help identify important patterns in the data.

### Step 5: Apply Advanced Formulas

Use SUM, AVERAGE, COUNTA, COUNTIF, IF, VLOOKUP, and INDEX/MATCH to calculate results and retrieve information.

### Step 6: Create Charts

Use the Visualizations sheet to compare country sales, examine monthly sales trends, and identify products with high sales.

### Step 7: Build the Dashboard

Open the Dashboard sheet. Review the KPI cards and use the country and month dropdown filters to change the displayed figures.

### Step 8: Review the Results

Check the charts, summary tables, and KPI values. Confirm that the figures are consistent with the cleaned dataset.

### Step 9: Save the Workbook

Save the complete project as an Excel Workbook (`.xlsx`) so that all sheets remain together in one file.

## 5. Dashboard KPI Cards

* **Total Sales:** Total value of sales for the selected filters.

* **Units Sold:** Total quantity sold.

* **Invoice Lines:** Number of transaction records included.

* **Unique Customers:** Number of distinct customers represented in the data, where the calculation supports a distinct count.

## 6. Charts and Their Explanations

### Chart 1: Sales by Country

Compares sales across countries and helps identify the countries contributing the most sales.

### Chart 2: Monthly Sales Trend

Shows how sales change from month to month and helps identify increases, decreases, and seasonal patterns.

### Chart 3: Top Products by Sales

Compares products according to their total sales value and helps identify high-performing products.

### Chart 4: Units Sold by Country

Compares quantities sold across countries. This helps distinguish sales volume from sales value.

## 7. Dashboard Filters
<img width="1185" height="695" alt="DASHHBOARD" src="https://github.com/user-attachments/assets/e33f6399-6b51-47f7-aba3-987721662fa5" />


**Country Filter:** Select a country to view its sales information, or select All Countries to view the complete dataset.

**Month Filter:** Select a month to examine sales for that period, or select All Months to view all available months.

The filters are designed to update the KPI cards and dashboard charts where configured.

## 8. Excel Skills Demonstrated

* Data import and cleaning

* Duplicate and missing-value handling

* Number and date formatting

* Excel formulas and functions

* Summary-table creation

* Data visualization

* Dashboard layout and formatting

* Dropdown-based filtering

* Workbook documentation

## 9. Important Notes

* Keep the Raw Data sheet unchanged so that the original data remains available.

* Use Cleaned Data for analysis.

* Check formulas whenever new records are added.

* Refresh summary tables and charts if their source data changes.

* Verify dashboard calculations before using the results in a report.

* Save your work regularly.

## 10. Conclusion

The Retail Sales Analysis & Interactive Dashboard project demonstrates how Excel can transform raw transaction data into useful summaries, charts, and interactive reports. It combines data preparation, formulas, visualization, and dashboard design in one workbook to make sales information easier to understand.

## Suggested README sheet formatting

* Title: Dark blue background with white bold text.

* Section headings: Light blue background with bold text.

* Instructions: Simple language with numbered steps.

* Charts: Add small chart images or screenshots beside their explanations if you want a visual README.

* Gridlines: Keep gridlines enabled.

* Text wrapping: Turn on Wrap Text for long descriptions.

Important: The four chart descriptions above correspond to the dashboard layout we discussed. If your current workbook contains different chart titles, update the README titles to match the actual charts.
