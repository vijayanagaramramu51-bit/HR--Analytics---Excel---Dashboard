
# HR Capstone Data Analytics Dashboard

An end-to-end Excel data analytics project focused on workforce performance, employee retention, and engagement analysis. This project transforms raw HR data into an interactive, insight-driven dashboard using advanced Excel techniques like dynamic pivot tables, data modeling, and search portals built via lookup functions.

## 📊 Project Components
The workbook contains four main core sheets:
* *Data Sample (HR_capstone_dataset):* The clean source dataset containing employee names, IDs, satisfaction metrics, evaluations, monthly hours, project counts, departments, and retention statuses.
* *Pivot Tables:* Four distinct analytical summaries mapping out attrition volume, performance vs. engagement disconnects, workload utilization, and compensation turnover trends.
* *Lookup Tool:* A search utility using VLOOKUP and XLOOKUP formulas to query individual employee records dynamically.
* *Dashboard:* A central, visual monitoring interface using dynamic charts, design layouts, and slicers for seamless stakeholder reporting.

---

## 📈 Key Insights & Analytical Focus

### 1. Departmental Attrition Volume
* Evaluates the absolute volume of employees who have left (Sum of Left) segmented by business units.
* Highlights high-risk attrition departments (e.g., Sales and Technical groups) to focus retention policies where they matter most.

### 2. Performance vs. Engagement Disconnect
* Breaks down the correlation between an employee's average satisfaction level and their last performance evaluation.
* Identifies departments where high-performing staff report low satisfaction scores, signalling hidden turnover risks.

### 3. Workload Utilization & Burnout Audit
* Cross-references the number of projects handled by employees against their average monthly working hours.
* Highlights severe operational bottlenecks where a heavy project count directly scales up average monthly hours, leading to burnout.

### 4. Turnover Rate by Compensation Band
* Calculates the precise percentage of employee turnover (Average of Left) across different salary tiers (Low, Medium, High).
* Validates how competitive compensation models directly impact retention curves.

---

## 🛠️ Advanced Excel Toolkit Applied

* *Dynamic Data Summaries:* Leveraged multi-variable Pivot Tables to isolate categorical trends without mutating the underlying master dataset.
* *Data Engineering & Lookups:* Used XLOOKUP and VLOOKUP functions to assemble an on-demand employee search portal, extracting individual row features instantly.
* *Interactive Visualization:* Deployed a visual KPI dashboard using customized combo charts, bar breakdowns, and contextual data series.
* *UI/UX Optimization:* Integrated interactive Slicers (such as Department and Salary tiers) to allow stakeholders to filter the workspace fluidly with a single click.

---

## 📂 Dataset Architecture
The primary table tracks the following key structural attributes:
* Employee_Name / Employee_Id — Unique individual identifiers.
* Satisfaction_Level — Continuous metric measuring internal employee happiness (0.0 to 1.0).
* Last_Evaluation — The latest supervisor performance appraisal rating.
* Number_Project — Count of active operational workflows assigned.
* Average_Monthly_Hours — Cumulative time investment per employee per month.
* Work_Accident — Binary indicator of on-the-job safety incidents.
* Left — Target attrition outcome variable (1 if departed, 0 if active).
* Promotion_Last_5Years — Historical promotion status marker.
* Department / Salary — Operational grouping and categorical compensation classification.
An interactive HR Capstone Analytics Dashboard built in Excel utilizing advanced Pivot Tables, dynamic charts, and XLOOKUP/VLOOKUP search tools to analyze workforce retention, burnout patterns, and department-level attrition trends
