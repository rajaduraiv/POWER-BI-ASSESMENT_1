# Power BI Assessment 1

## Project Title

**Power BI Data Analysis and Visualization**

## File Name

`POWER BI ASSESMENT_1.pbix`

## Description

This Power BI project was created to analyze and visualize data using interactive charts and date-based analysis. The report uses the **Shopify Stock** data along with the **Dim_Date** table to present meaningful information in a visual format.

The Power BI report contains visualizations that help understand stock-related values across different time periods.

## Tools Used

* Microsoft Power BI Desktop
* Power Query
* Data Modeling
* DAX / Power BI aggregations
* Charts and Visualizations

## Data Used

The Power BI file contains the following main data sources/tables:

### 1. Shopify Stock

The **Shopify Stock** table contains stock-related information. The report uses the `low` field for aggregation and visualization.

### 2. Dim_Date

The **Dim_Date** table is used for date-based analysis. The report uses the date hierarchy containing:

* Year
* Quarter
* Month
* Day

## Operations Performed in Power BI

### 1. Imported the Data

The required dataset was loaded into Power BI Desktop for analysis and visualization.

### 2. Data Preparation

The available data was prepared in Power BI so that the required fields could be used for analysis and visualizations.

### 3. Date Analysis

A date dimension/table was used for time-based analysis.

The date hierarchy was used at different levels:

* Year
* Quarter
* Month
* Day

This allows the data to be analyzed from a yearly level down to a daily level.

### 4. Data Modeling

The **Shopify Stock** and **Dim_Date** tables were used in the Power BI data model to support date-based analysis.

### 5. Aggregation

The `low` field from the **Shopify Stock** table was aggregated using **Sum** for visualization.

The aggregation is used to understand the total value of the selected stock field.

### 6. Created Bar Chart

A **Bar Chart** was created to visualize the aggregated stock value across the **Year** level of the date hierarchy.

The chart uses:

* **Axis/Category:** Date Year
* **Values:** Sum of Shopify Stock `low`

### 7. Created Column Chart

A **Column Chart** was created for time-based visualization.

The chart uses the date hierarchy containing:

* Year
* Quarter
* Month
* Day

This provides a hierarchical view of the data over time.

### 8. Used Date Hierarchy

The built-in Power BI date hierarchy was used to analyze information at multiple levels.

The hierarchy allows the user to move between:
**Year → Quarter → Month → Day**

### 9. Applied Filters

Filters were configured for the visualizations to support analysis based on the available fields.

The report includes filtering at different levels of the date hierarchy and the stock value.

### 10. Enabled Visual Interaction

Visual interactions/drill-related behavior were configured so that selecting data in one visualization can affect the analysis of other visuals.

### 11. Report Formatting

The report page and visual containers were arranged to provide a clear and organized dashboard-style presentation.

## Visualizations Created

### Bar Chart

The bar chart represents the **sum of the low stock value by year**.

### Column Chart

The column chart represents data using the **date hierarchy**, allowing analysis across year, quarter, month, and day.

## Key Power BI Concepts Used

* Data Import
* Data Preparation
* Data Modeling
* Date Dimension
* Date Hierarchy
* Aggregation
* Sum Function
* Bar Chart
* Column Chart
* Filters
* Drill/Hierarchy Analysis
* Visual Interactions
* Report Formatting

##Output

<img width="1915" height="973" alt="Screenshot 2026-09-22 104437" src="https://github.com/user-attachments/assets/c3f4ed89-f375-4610-b21f-69a15616d1af" />

## Objective

The main objective of this assessment is to practice using Power BI for data preparation, modeling, aggregation, time-based analysis, and interactive data visualization.

## Conclusion

The Power BI assessment demonstrates how raw data can be transformed into meaningful visual information. By using the Shopify Stock and Dim_Date tables, the report provides time-based stock analysis through bar and column charts. The use of date hierarchies, aggregation, filtering, and visual interactions makes the report useful for exploring the data at different levels of detail.
