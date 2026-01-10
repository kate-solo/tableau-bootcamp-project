# Employee Attrition — Key Insights & Drivers

A data-driven analysis of employee attrition patterns using the IBM HR Analytics dataset.  
The project combines exploratory data analysis (EDA) and visual analytics to identify key factors influencing workforce turnover and to support informed HR decision-making.

---

## 📌 Project Overview

Employee attrition is a critical challenge for organizations, impacting productivity, costs, and long-term performance.  
This project explores employee attrition through demographic, compensation, tenure, satisfaction, and work-life balance variables.

The analysis aims to answer:
- What is the overall attrition rate?
- Which departments are most affected?
- How do job satisfaction and work-life balance relate to attrition?
- What demographic and compensation patterns distinguish employees who leave?

---

## 📂 Repository Structure

- `IBM_HR_Employee_Attrition.csv` — Original dataset  
- `IBM_HR_Employee_Attrition_cleaned.csv` — Cleaned dataset used for analysis  
- `IBM_HR_Employee_Attrition.ipynb` — EDA and data preparation notebook  
- `project_1_ibm_hr_employee_attrition.twbx` — Tableau packaged workbook  
- `README.md` — Project documentation

---

## 🧹 Data Preparation & EDA

The data preparation process includes:
- Handling missing and inconsistent values
- Feature inspection and type validation
- Creation of derived variables for analysis
- Exploratory analysis using Python (Pandas, Matplotlib, Seaborn)

Key EDA focus areas:
- Attrition distribution
- Department-level attrition
- Job satisfaction and work-life balance patterns
- Age, tenure, and income differences by attrition status

---

## 📊 Visual Analytics (Tableau)

The Tableau workbook presents insights through a structured analytical story:

### Story Sections
1. **Executive Overview**
   - Overall attrition distribution and rate
   - Attrition by department
   - High-level key insights

2. **Drivers & Patterns**
   - Average age, tenure, and income by attrition status
   - Attrition by job satisfaction level
   - Attrition by work-life balance

3. **Recommendations & Limitations**
   - Practical retention-focused recommendations
   - Analytical limitations and assumptions

4. **Conclusions**
   - Summary of key findings and strategic implications

The visualizations are designed following best practices:
- Clear hierarchy and consistent styling
- Minimal visual noise
- Insight-driven titles and annotations

---

## 🔍 Key Insights

- Overall attrition rate is approximately **16%**
- Higher attrition concentrations are observed in **Sales** and **Research & Development**
- Employees who leave tend to be:
  - Younger
  - With shorter tenure
  - Earning lower monthly income
- Lower job satisfaction and poorer work-life balance are strongly associated with higher attrition

---

## 🧠 Recommendations

- Focus retention strategies on early-career employees
- Improve job satisfaction through engagement and role alignment
- Strengthen work-life balance initiatives
- Monitor high-risk departments more closely

> Note: Results are based on historical data and represent associations rather than causal relationships.

---

## ⚠️ Limitations

- The dataset represents a single organization (IBM)
- No causal inference is applied
- External economic or organizational factors are not included

---

## 🛠 Tools & Technologies

- **Python**: Pandas, Matplotlib, Seaborn
- **Tableau**: Interactive dashboards and story
- **GitHub**: Version control and project sharing

---

## 📎 Dataset Source

IBM HR Analytics Employee Attrition Dataset  
(Provided for educational and analytical purposes)




