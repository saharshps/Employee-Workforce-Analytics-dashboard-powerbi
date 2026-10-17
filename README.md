# Employee Workforce Analytics Dashboard

An interactive Power BI dashboard for exploring employee workforce metrics across business units, departments, demographics, countries, cities, and time.

## Dashboard Preview

<img width="1426" height="861" alt="Screenshot (215)" src="https://github.com/user-attachments/assets/2cbc7aae-0899-43be-a729-2c925e8f563c" />


## Overview

The **Employee Workforce Analytics** dashboard provides a high-level view of workforce size, compensation, department distribution, gender composition, and geographic salary patterns. Interactive slicers allow users to filter the report by **Business Unit**, **Ethnicity**, and **Year**.

## Key Performance Indicators

The report's top-level cards display:

- **Total Employees** — overall employee count (shown as approximately 1K in the screenshot).
- **Average Salary** — average salary (shown as `$754.46` in the current view).
- **Average Bonus** — average bonus percentage (shown as `7.98%`).
- **Total Departments** — number of departments (shown as `8`).
- **Total Cities** — number of cities (shown as `14`).
- **Total Countries** — number of countries (shown as `4`).

*Values reflect the filters and data visible in the screenshot and may change when slicers are used.*

## Visuals and Insights

### 1. Department vs Salary
A column chart compares the sum of annual salary across departments. In the displayed view, IT has the highest total, followed by Sales and Engineering.

### 2. Gender Distribution
A doughnut chart shows the employee distribution by gender: **515 (51.5%)** and **485 (48.5%)** in the current view.

### 3. Monthly Salary Trend
A line chart plots average annual salary by month, helping users compare compensation patterns throughout the year.

### 4. Employee Count by Department
A horizontal bar chart compares employee counts across departments. IT has the highest displayed count (**277**), followed by Sales (**150**) and Engineering (**141**).

### 5. Annual Salary by Country
A waterfall chart compares annual salary totals across countries, including the United States, China, and Brazil, with a total shown in the current view.

### 6. Annual Salary by City
A ranked area/line-style chart compares total annual salary across cities, making it easier to identify higher- and lower-total locations.

## Interactive Filters

Use the slicers at the top of the report to filter the dashboard by:

- **Business Unit**
- **Ethnicity**
- **Year**

The visuals and KPI cards are intended to respond to the selected filters.

## Tools

- **Microsoft Power BI Desktop**
- Power Query for data preparation (if used in the project)
- DAX measures for calculated KPIs (if used in the project)

## Getting Started

1. Clone or download this repository.
2. Open the `.pbix` report in **Power BI Desktop**.
3. If prompted, connect or refresh the source data.
4. Use the slicers to explore the workforce metrics.


Rename the `.pbix` file in this example to match the actual report filename in your repository. Include the source dataset only if you have permission to share it and it contains no sensitive employee information.

## Notes

- Metrics shown here are based on the screenshot and may vary with filters or dataset changes.
- Confirm the units and definitions of salary and bonus measures in the Power BI model before using the report for business decisions.
- Do not publish confidential employee-level data, personally identifiable information, or restricted company data in a public repository.

## Author

**Your Name**  
Add your GitHub profile or portfolio link here.
