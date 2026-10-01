# Hospital Emergency Room Analytics Dashboard

An interactive **Hospital Emergency Room Analytics Dashboard built in Microsoft Excel** to analyze patient volume, wait time, satisfaction, admission status, demographics, timeliness, and department referrals.

## Project Objective

The objective of this project is to transform hospital emergency-room data into an interactive monthly dashboard that helps users monitor operational KPIs and explore patient patterns through filters and visualizations.

## Tools & Technologies

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- PivotTables
- Excel Charts & Sparklines

## Project Workflow

1. Business requirement gathering
2. Data understanding
3. Data import using Power Query
4. Data cleaning and quality checks
5. Calendar table creation
6. Data modeling using Power Pivot
7. Calculated fields using DAX
8. PivotTable and dashboard development
9. Chart development and formatting
10. Insight generation

## Dashboard KPIs

- Number of Patients
- Average Wait Time
- Patient Satisfaction Score
- Patient Attend Status
- Admission Status
- Gender-wise Patient Distribution
- Patient Age Distribution
- Department Referrals

## DAX Calculations

### Age Group

The project uses a DAX calculated column to classify patients into age groups such as `0-9`, `10-19`, `20-29`, `30-39`, `40-49`, `50-59`, `60-69`, and `70-79`.

### Patient Attend Status

Patients are classified based on wait time into attendance categories such as **Within Time** and **Delay**.

## Dashboard

![Hospital Emergency Room Dashboard](screenshots/dashboard.png)

The dashboard provides monthly analysis with year/month selection and visualizes patient volume, average wait time, satisfaction, admission status, timeliness, gender, age distribution, and department referrals.

## Project Files

- `Hospital_ER_Analytics_Dashboard.xlsx` — Excel workbook containing the dashboard, calculations, PivotTables, and supporting sheets.
- `screenshots/dashboard.png` — Final dashboard screenshot.
- `screenshots/daily-patient-trend.png` — Daily patient trend visualization.
- `screenshots/patient-satisfaction-trend.png` — Daily satisfaction trend visualization.

## Notes

The dashboard is designed for monthly reporting. The displayed KPI values change according to the selected year/month filters.
