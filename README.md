# Leads Analysis Power BI Report

## Project Overview
This Power BI report analyzes leads data to provide insights into lead conversion, source impact, activity distribution, and key metrics. The report is designed to help stakeholders understand the performance of various lead sources and specializations, as well as overall engagement metrics.

## Data Preparation
The data used in this report was prepared using the following steps:
1. **Data Cleaning:**
   - Replaced placeholder values such as 'Select' with nulls.
   - Imputed missing values for key fields (e.g., City).
   - Created cleaned and imputed columns for analysis.

2. **Data Transformation:**
   - Created calculated columns to replace blanks with meaningful values (e.g., 'Unknown').
   - Added flag columns to indicate imputed values.
   - Aggregated and summarized data for visualization.

## Report Structure

### 1. Visual Analysis Page
This page contains a variety of visuals providing an overview of lead data:
- **Clustered Bar Chart:** Shows the number of conversions by specialization.
- **Stacked Column Chart:** Displays the impact of lead sources on conversions, further broken down by specialization.
- **Pie Chart:** Illustrates the distribution of leads by city.
- **Scatter Chart:** Analyzes the relationship between total time spent on the website and conversions.
- **Slicers:** Interactive slicers for `Lead Source` and other key dimensions to filter the data.

### 2. Drillthrough Details Page
This page provides detailed information on leads based on the drillthrough context:
- **Detailed Table:** Lists leads with columns such as `Prospect ID`, `Lead Number`, `Lead Source`, `Specialization`, and `Converted`.
- **Additional Visuals:** Includes pie charts and bar charts to provide more context on the drillthrough data.

### 3. Summary Dashboard
The summary dashboard highlights key metrics for a quick overview:
- **Summary Cards:** Display total time spent on the website, total visits, total conversions, and other key metrics.
- **Multi-Row Cards:** Show additional key metrics for comprehensive analysis.

## Enhancements and Interactivity
- **Tooltips:** Customized tooltips to provide additional context when hovering over data points.
- **Bookmarks and Navigation:** Bookmarks and buttons for easy navigation and interaction within the report.
- **Consistent Formatting:** Applied themes and customized formatting to ensure a cohesive and user-friendly report.
- **Drillthrough Capabilities:** Enabled drillthrough to provide detailed insights from high-level visuals.

## Performance Optimization
- **Data Model Optimization:** Removed unnecessary columns and tables, and used data reduction techniques.
- **Visual Performance:** Limited the number of visuals on a single page and optimized measures and calculated columns.

## Sharing and Collaboration
- **Published Report:** Published the report to Power BI service for sharing and collaboration.
- **Dashboards:** Created dashboards to pin key visuals for at-a-glance insights.
- **Collaboration Features:** Used Power BI's collaboration features such as comments and shared datasets to facilitate teamwork.

## Conclusion
This Power BI report provides a comprehensive analysis of leads data, with interactive and detailed visuals, summaries, and drillthrough capabilities. It is designed to help stakeholders gain valuable insights into lead performance and make data-driven decisions.

---

