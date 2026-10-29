# Global Retail Sales Analytics 📊


## 📌 Project Overview
Transformed a raw, unformatted dataset of over 2,800 global retail transactions into a dynamic, interactive financial dashboard. The objective was to clean inconsistent data, engineer new financial metrics using relational logic, and build an automated visual interface for executive decision-making.

## 🛠️ Tools & Techniques Used
*   **Microsoft Excel:** Data Cleaning, Advanced Formulas, Logical Functions, Statistical Aggregation.
*   **Functions:** `IF`, `IFS`, `INDEX-MATCH`, `SUM`, `AVERAGE`, `MEDIAN`, `MODE.SNGL`, `STDEV.S`.
*   **Data Visualization:** PivotTables, custom PivotCharts, and multi-report connected Slicers.

## 🚀 Project Workflow

### 1. Data Cleaning & Standardization
*   Converted raw CSV data into a dynamic Excel Table for scalable formula application.
*   Resolved complex regional date-formatting conflicts (translating US MDY to Indian DMY) using the Text-to-Columns parsing engine to ensure accurate temporal grouping.

### 2. Logical Modeling & Relational Lookups
*   **Status Flagging (`IF`):** Engineered an `Action_Required` column to automatically isolate "Cancelled" or "Disputed" orders for back-office review.
*   **Relational Mapping (`XLOOKUP`):** Designed a separate reference data architecture to map dynamic 'Target Margins' to specific product lines, enabling the automated calculation of projected profit per transaction.

### 3. Statistical Summary Board
*   Constructed a clean, structural summary matrix utilizing Excel table references to calculate baseline operational metrics, including Total Revenue ($10M+), Average Order Value, Median Sale, and Sales Standard Deviation.

### 4. Interactive Executive Dashboard
*   Developed a grid-free, executive-level visual interface.
*   Integrated descending-sorted Column and Bar PivotCharts to identify top-performing product lines and geographic regions.
*   Wired interactive Slicers (`YEAR_ID` and `DEALSIZE`) to multiple PivotTables simultaneously, allowing users to filter the entire dashboard with a single click.

## 💡 Key Business Insights
1.  **Core Revenue Drivers:** Classic Cars and Vintage Cars dominate the product hierarchy, generating the overwhelming majority of the $10M+ total revenue.
2.  **Geographic Dominance:** The USA market significantly outperforms all other regions, producing nearly triple the sales volume of the second-highest market (France).

## 📂 How to View This Project
1.  Download the `SalesData_Dashboard.xlsx` file from this repository.
2.  Open in Microsoft Excel .
3.  Navigate to the **Dashboard** tab to interact with the data, or view the **SalesData** tab to inspect the logical lookup formulas.
