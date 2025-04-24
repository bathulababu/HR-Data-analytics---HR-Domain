# HR-Data-analytics---HR-Domain

This Power BI dashboard provides an overview of employee presence and attendance for AtliQ. It allows users to see daily attendance status and identify patterns over a period.

## Key Features

* **Daily Employee Presence:** Shows the attendance status of each employee for each day in the selected period (June 1st to June 11th as visible).
* **Presence Status Codes:** Utilizes codes to represent different presence statuses (e.g., P, WO, SL, PL, WF, ML, BRL).
* **Employee List:** Displays a list of employee names and their corresponding employee codes.
* **Date Range:** Covers a specific date range, allowing for focused analysis of attendance trends within that period.

## Visualizations Included

* **Matrix-like Table:** The primary visualization is a table displaying employees on the rows and dates on the columns, with presence codes in the cells.

## Data Sources

The dashboard is built using employee attendance data, likely from a system that records daily presence. The key columns appear to be:

* **Employee Code:** A unique identifier for each employee (e.g., Atq-462).
* **Name:** The full name of the employee (e.g., Thanos Thakur).
* **Date Columns:** Columns representing individual dates (e.g., 1-Jun, 2-Jun, ..., 11-Jun).
* **Presence Status:** The value within each date column indicates the employee's status for that day. The following codes are observed:
    * **P:** Present
    * **WO:** Week Off
    * **SL:** Sick Leave
    * **PL:** Paid Leave
    * **WFH:** Work From Home
    * **ML:** Maternity Leave
    * **BRL:** Bereavement Leave

## How to Use

* **Review Daily Status:** Examine the table to see the attendance status of each employee on a specific day.
* **Identify Absences:** Look for codes other than 'P' to identify employees who were not present and the reason for their absence.
* **Analyze Patterns:** Observe trends in attendance for individual employees or across the team over the given date range.

## Potential Use Cases

* Tracking daily employee attendance.
* Identifying employees who are frequently absent or taking leave.
* Monitoring adherence to work schedules and leave policies.
* Providing data for payroll and HR purposes.

---

**Note:** This README is based on the limited data visible in the spreadsheet image. A more comprehensive README would include details about the source system, the full range of presence status codes and their definitions, the process for updating the data, and any interactive elements within the Power BI dashboard.
