# 📊 Data Professional Survey Analysis Dashboard

## 🎯 Objective
To analyze survey data collected from data professionals, clean and transform the data using Power Query, and build an interactive dashboard in Power BI Desktop. The dashboard visualizes key insights about demographics, roles, salaries, programming languages, and job satisfaction.

## 📁 Data Source
The dataset comes from a survey conducted among data professionals and is provided as an Excel/CSV file containing raw responses.

## 🔧 Key Transformations & Cleaning Steps

1. **Data Loading:** Imported the raw survey data into Power BI Desktop.
2. **Power Query Transformations:**
   - Removed unnecessary columns (e.g., Browser, OS, Referrer).
   - Cleaned and standardized categorical data in columns like Job Title, Programming Language, Industry, and Country.
   - Handled free-text entries like “Other (Specify)” by isolating the primary category.
   - Processed the 'Current Yearly Salary' column:
     - Split text ranges (e.g., "106k-125k") into min/max.
     - Converted them into numerical values.
     - Calculated average salary from the min/max.
     - Properly set data types (e.g., Decimal for salary).
3. **Data Modeling:** Single table model with no explicit relationships.

## 📊 Visualizations Created
- Card visuals: Total Respondents, Average Age
- Bar Chart: Average Salary by Job Title
- Column Chart: Programming Languages by Job Title
- Treemap: Respondent Distribution by Country
- Donut Chart: Average Salary by Gender
- Gauges: Happiness scores for Work/Life Balance and Salary
- Dynamic Title and Theme styling (‘Frontier’ theme with customized colors)

## 📦 Final Output
A one-page interactive Power BI dashboard featuring:
- Clean and engaging layout
- Filterable and dynamic visuals
- Insights into data professionals’ roles, tools, satisfaction, and salaries

## 🗂️ Files Included

- `data_professional_survey_raw.xlsx`
- `data_professional_survey_cleaned.csv`
- `data_professional_survey.pbix`
- `data_professional_survey.png`
