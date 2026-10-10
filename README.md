# HR Dashboard Project (Excel)

Interactive Excel dashboard analyzing workforce size, attrition, gender mix and salary across hospital departments.



![HR Dashboard](HR%20Dashboard%20Project.png)



## Business Problem
How big is the workforce, who is leaving, and how do headcount and salary differ across departments, job roles and gender?

## Dataset
- [Source: self-created / public HR dataset: write what is true]
- 1,001 employee records, [X] columns
- Columns include: EmployeeID, Gender, Department, Job Role, Education Field, Age, Salary, Attrition

## Data Cleaning
- Removed [X] duplicate records
- Fixed [missing values / text errors / formats]
- Corrected pivot tables to use Count of EmployeeID instead of Sum

## KPIs Tracked
- Employee Count: 1,001
- Average Age: about 37 years
- Average Salary: about 6,615
- Maximum Salary: 19,999
- Minimum Salary: 1,009
- Attrition Rate: about 12.7%

## Charts
- Workforce by Department
- Employee Gender Distribution
- Employee Attrition Rate
- Average Salary by Department

## Key Insights
1. **Attrition:** 127 of 1,001 employees left (about 12.7%), and 874 stayed.
2. **Gender:** The workforce is about 76% male (759) and 24% female (242).
3. **Department:** Maternity has the largest workforce and Neurology the smallest.
4. **Salary by department:** Neurology has the highest average salary (about 11,016), roughly double Maternity, the lowest (about 5,122). Cardiology is about 7,072.
5. **Salary range:** Salaries range from 1,009 to 19,999, with an overall average of about 6,615.

## Recommendations
- Use the Department, Job Role and Education Field slicers to find where attrition is highest, then focus retention efforts there
- Review the pay gap between Neurology and Maternity
- Improve gender balance in hiring, since women are only about 24% of the workforce
- Track attrition monthly to catch problems early

## Dashboard Features
- KPI cards for headcount, age, salary and attrition
- Slicers for Gender, Department, Job Role, Attrition and Education Field
- Pivot tables and interactive charts

## Challenges and Solutions
- **Wrong aggregation:** A pivot table added up EmployeeID numbers, which has no meaning. I changed it to Count of EmployeeID so it shows the real headcount.
- **Chart titles:** I gave each chart a clear title, such as "Average Salary by Department" and "Employee Attrition Rate".

## Tools Used
Microsoft Excel: Pivot Tables, Formulas, Charts, Slicers

## Files
- `HR Dashboard Project.xlsx`: full workbook with dashboard, pivot tables and data
- `HR Dashboard Project.png`: dashboard preview

## Contact
Vignesh K | vigneshkarna2005@gmail.com | [LinkedIn](https://www.linkedin.com/in/vignesh-k-a46146368)
