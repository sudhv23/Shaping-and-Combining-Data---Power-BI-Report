# 📊 Shaping and Combining Data - Power BI Report

This Power BI report demonstrates the process of importing, shaping, and combining data from multiple Excel files to create a clean and unified dataset for business reporting at AdventureWorks.

## ✅ Tasks Completed

### 📥 Data Import
- Imported `sales-Europe.xlsx` and loaded the **Europe** table.
- Imported `sales-North America.xlsx` and opened the **North America** table in Power Query Editor.

### 🧹 Data Transformation
- Removed unnecessary columns: `ProductKey`, `SalesOrderNumber`.
- Renamed columns for consistency:
  - `SalesTerritoryCountry` → `Country`
  - `SalesTerritoryGroup` → `Sales Territory`
  - `EnglishProductCategoryName` → `Main Category`
  - `EnglishProductSubcategoryName` → `Sub Category`
  - `EnglishProductName` → `Product`
- Moved the `Color` column to the left.
- Applied the same transformations to both **Europe** and **North America** queries.

### 🔗 Data Combination
- Appended the **Europe** and **North America** queries into a single table.
- Imported `country code.xlsx` and merged it with the appended table.
- Extracted and renamed the `Code` column to `Country Code`.
- Reordered the `Country Code` column to appear first.

## 📁 File

- `Shaping and Combining Data.pbix`: Power BI report file

## 💻 How to Use

1. Open the `.pbix` file in **Power BI Desktop**.
2. Review and extend the data model or visuals as needed for dashboarding in **Power BI Service**.
