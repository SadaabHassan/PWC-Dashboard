# PWC-Dashboard
### Dashboard Link: [Power BI Report](https://app.powerbi.com/groups/me/reports/3a2fd3ea-5703-4e8c-b4b4-a633b6c8cbb0/da7990c30001577e006d?experience=power-bi)  

## Problem Statement  

This dashboard helps organizations analyze employee attrition trends and HR metrics. It provides insights into key factors influencing attrition rates, employee satisfaction, and areas for improvement. By leveraging data visualization, HR teams can take informed actions to enhance employee experience and reduce attrition.  

## Key Insights  

- Displays the proportion of employees who have left versus those who remain.  
- Identifies key factors contributing to attrition, such as job role, department, salary, and work-life balance.  
- Provides insights into employee satisfaction based on ratings.  
- Tracks attrition trends over time and across different segments.  

## Steps Followed  

1. **Data Preparation:**  
   - Imported datasets in CSV format into Power BI Desktop.  
   - Used Power Query Editor for data validation (Column Distribution, Column Quality, and Column Profile enabled).  
   - Ensured column profiling covered the entire dataset.  
   - Identified and handled missing/null values.  

2. **Data Transformation & Measures:**  
   - Created calculated measures for analyzing tenure, salary distribution, and satisfaction scores.  
   - Added age group segmentation using DAX:  

   ```DAX
   Age Group =
   IF(EmployeeData[Age] <= 25, "0-25 (25 included)",
   IF(EmployeeData[Age] <= 50, "25-50 (50 included)",
   IF(EmployeeData[Age] <= 75, "50-75 (75 included)",
   "75-100 (100 included)")))
   ```  

3. **Visualization & Dashboard Design:**  
   - **Card visuals** for key metrics (Attrition Rate, Average Tenure, Job Satisfaction).  
   - **Bar charts** comparing attrition across departments and roles.  
   - **Pie charts** showing employee distribution based on attributes.  
   - **Line charts** tracking attrition trends over time.  
   - **Satisfaction Ratings Visual** covering Work Environment, Career Growth, Work-Life Balance, etc.  

4. **Enhancements & Branding:**  
   - Incorporated a company logo, name, and tagline for professional presentation.  
   - Applied interactive filters/slicers for insights on department, job role, work experience, and education level.  

---

## Additional Experience  

I recently completed **PwC Switzerland’s Power BI Virtual Experience** on Forage. This simulation enhanced my Power BI skills and data-driven decision-making capabilities. Key takeaways:  

✔ Strengthened ability to understand client needs and create impactful visualizations.  
✔ Designed dashboards showcasing key KPIs with well-structured insights.  
✔ Communicated findings effectively through concise, insightful reports.  
✔ Applied analytical problem-solving to HR data, identifying gender balance issues at the executive level and providing data-driven recommendations.  

![Image](https://github.com/user-attachments/assets/15e41182-6492-407c-83f1-dee3661d63bc)
