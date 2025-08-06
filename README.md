# **HR Employee Attrition Analysis**

## 1. Problem Statement
Employee attrition (resignations) is a major challenge for organizations, leading to:
- High hiring and training costs  
- Loss of skilled talent  
- Reduced productivity  

The HR department wants to analyze employee data to identify:  
- Why employees are leaving  
- Which factors contribute most to attrition  
- Data-driven strategies to reduce turnover  


## 2. Objective / Goal
- Analyze employee attrition patterns  
- Understand the impact of **salary, work-life balance, job satisfaction, and overtime**  
- Provide **actionable insights** to HR for improving employee retention  


## 3. Dataset Description
The dataset contains **500 employee records** with the following fields:

| Column Name              | Description                                  |
|--------------------------|----------------------------------------------|
| EmployeeID               | Unique employee ID                            |
| Age                      | Age of the employee                           |
| Gender                   | Male / Female                                 |
| Department               | HR, Sales, Development, Finance, Support      |
| JobRole                  | Manager, Analyst, Developer, Consultant, etc. |
| MonthlyIncome            | Employee salary per month                     |
| JobSatisfaction          | Satisfaction level (1 to 5)                   |
| WorkLifeBalance          | Work-life balance rating (1 to 5)             |
| YearsAtCompany           | Total years worked in the company             |
| TrainingTimesLastYear    | Training frequency                            |
| Overtime                 | Yes / No                                      |
| Attrition                | Yes / No (Target variable)                    |


## 4. Analysis Approach
1. **Data Loading & Cleaning**  
   - Load dataset using Pandas  
   - Handle missing values & duplicates  
   - Convert categorical columns to proper types  

2. **Exploratory Data Analysis (EDA)**  
   - Calculate overall attrition rate  
   - Analyze attrition by **department, salary, gender, and overtime**  
   - Explore impact of **work-life balance & job satisfaction**  
   - Visualize results using **Matplotlib & Seaborn**  

3. **Insights & Recommendations**  
   - Identify patterns & risk factors for attrition  
   - Suggest HR strategies for retention  


## 5. Key Insights
1. High attrition in **Sales & Development** departments  
2. Employees with **low salaries & frequent overtime** are more likely to leave  
3. **Poor work-life balance (≤2)** significantly increases attrition risk  
4. Employees with **less than 2 years** in the company are more prone to resign  

## 6. Recommendations for HR
- Improve **work-life balance** and reduce overtime in critical teams  
- Offer **salary adjustments or incentives** to high-risk employees  
- Conduct **employee engagement & training programs**  
- Focus retention efforts on **new employees (0–2 years)**  


## 7. Business Impact
- Helps HR **identify high-risk employees** and reduce attrition  
- Potential to save **₹20–30 lakhs/year** in hiring and training costs  
- Improves **employee satisfaction and retention strategies**  


## 8. Tools & Technologies Used
- **Python** → Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook / VS Code / PyCharm**  
- **GitHub** → Portfolio hosting  


## 9. Key Visualizations
![Attrition by Department] 
![Monthly Income vs Attrition]
![Correlation Heatmap] 

## 10. Project Deliverables
- **Dataset**
- **Notebook** 
- **Visuals**  
- **README.md**   

## 11. How to Run
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/HR-Employee-Attrition-Analysis.git
   cd HR-Employee-Attrition-Analysis
