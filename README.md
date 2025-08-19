# HR Analytics Dashboard 📊  

## 📌 Overview  
The **HR Analytics Dashboard** is an interactive data visualization tool designed to analyze employee attrition trends and provide actionable insights into workforce management. It helps HR teams understand the key factors influencing employee retention, workforce demographics, and job satisfaction across different departments, age groups, and education fields.  

This dashboard aims to:  
- Identify **attrition trends** across departments, genders, age groups, and education fields.  
- Highlight **employee satisfaction levels** based on job roles.  
- Provide HR leaders with **data-driven insights** for decision-making.  

---

## 🚀 Features  
- **KPI Metrics at a glance**:  
  - Total Employees: `606`  
  - Attrition Count: `89`  
  - Attrition Rate: `14.69%`  
  - Active Employees: `517`  
  - Average Age: `37`  

- **Department-wise Attrition**:  
  - HR, R&D, and Sales attrition trends visualized in pie charts.  

- **Education Field-wise Attrition**:  
  - Attrition distribution across Life Sciences, Medical, Marketing, Technical Degree, Human Resources, and Others.  

- **Age Group Analysis**:  
  - Employee distribution by age groups.  
  - Attrition rate comparison across different age brackets.  

- **Gender Insights**:  
  - Attrition by gender (Male vs Female).  
  - Gender-based attrition across age groups.  

- **Job Satisfaction Ratings**:  
  - Satisfaction scores (1–4) across multiple job roles such as Managers, Sales Executives, Scientists, etc.  

- **Interactive Filters**:  
  - Filter analysis by **Education level** to dynamically update all visuals.  

---

## 📊 Insights from the Dashboard  
1. Majority of employees are between **25–35 years**, with the highest attrition in this age group.  
2. **Life Sciences** and **Medical fields** have the most attrition.  
3. **Sales** and **R&D** departments face higher attrition compared to HR.  
4. Males contribute slightly more to attrition than females.  
5. **Job satisfaction scores** vary significantly by role, with Research Scientists showing relatively higher satisfaction.  

---

## 🛠️ Tech Stack  
- **Data Source**: HR Employee Dataset (structured in CSV/Excel)  
- **Data Processing**: Power Query / SQL (optional preprocessing)  
- **Visualization Tool**: Microsoft Power BI  
- **Deployment**: Power BI Service / GitHub repository for sharing `.pbix` file and screenshots  

---

## 📂 Project Structure  
```bash
├── data/
│   ├── HR_dataset.csv          # Raw dataset
│   ├── processed_data.csv      # Cleaned dataset for Power BI
├── dashboard/
│   ├── HR_Analytics.pbix       # Power BI Dashboard file
│   ├── HR_Analytics.png        # Dashboard screenshot
├── README.md                   # Project documentation
