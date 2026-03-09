👥 Employee Salary Dataset — Analysis Project
A structured Excel-based data analysis project that covers the full data lifecycle: from raw collection and cleaning to analysis and dashboard visualization.

📁 Project Structure
The workbook contains 4 sheets, each representing a stage in the analysis pipeline:
SheetDescriptionRaw DataOriginal dataset with 35 employee recordsData CleaningValidation checklist and blank-detection reportAnalysisStatistical summaries and insightsDashboardVisual KPI summary (Total Employees, Avg Salary, etc.)

📊 Dataset Overview

Records: 35 employees
Columns: 5 features

ColumnTypeDescriptionIDIntegerUnique employee identifierExperience_YearsIntegerYears of professional experienceAgeIntegerEmployee ageGenderCategoricalMale / FemaleSalaryIntegerAnnual salary (EGP)

🔍 Project Stages
1. 🗂️ Raw Data
Contains the unprocessed employee records as originally collected. This sheet serves as the source of truth for all downstream processing.
2. 🧹 Data Cleaning
A validation report built with Excel formulas that:

Counts blank values per column using COUNTBLANK()
Flags columns with missing data using conditional IF() logic
Produces a ✅ Clean / ⚠️ Has Blanks status for each field

3. 📈 Analysis
Performs statistical exploration on the cleaned data including salary distribution, experience trends, and gender-based comparisons.
4. 📋 Dashboard
An interactive summary view displaying key metrics:

👤 Total Employees
💰 Average Salary
🏆 Highest Salary
📅 Average Experience


🛠️ Tools Used

Microsoft Excel — Data storage, cleaning formulas, analysis, and dashboard


🚀 How to Use

Clone or download the repository
Open Employee_Salary_Dataset_Before_Analysis.xlsx in Microsoft Excel
Start with the Raw Data sheet to explore the original records
Review Data Cleaning to understand data quality
Explore Analysis for insights
Check the Dashboard for a high-level summary

Kareem

Data Science & Machine Learning Student Passionate about turning data into insights
