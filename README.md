# Employee-Attrition-Analysis
This project analyzes employee attrition data to understand key factors influencing employees' decisions to leave the company. By examining various attributes such as job roles, education levels, job satisfaction, and working conditions, the goal is to identify patterns and insights that can help improve employee retention strategies.

Data Description
The dataset includes the following columns:
1-Age: Age of the employee
2-Attrition: Whether the employee left the company (Yes/No)
3-BusinessTravel: Frequency of business travel
4-DailyRate: Daily rate of the employee
5-Department: Department where the employee works
6-DistanceFromHome: Distance from home to the workplace
7-Education: Education level of the employee
8-EducationField: Field of education
9-EmployeeCount: Number of employees
10-EmployeeNumber: Unique identifier for the employee
11-EnvironmentSatisfaction: Satisfaction with the work environment
12-Gender: Gender of the employee
13-HourlyRate: Hourly rate of the employee
14-JobInvolvement: Level of job involvement
15-JobLevel: Job level of the employee
16-JobRole: Role of the employee within the company
17-JobSatisfaction: Satisfaction with the job
18-MaritalStatus: Marital status of the employee
19-MonthlyIncome: Monthly income of the employee
20-MonthlyRate: Monthly rate of the employee
21-NumCompaniesWorked: Number of companies worked for
22-Over18: Whether the employee is over 18
23-OverTime: Whether the employee works overtime
24-PercentSalaryHike: Percentage salary hike
25-PerformanceRating: Performance rating of the employee
26-RelationshipSatisfaction: Satisfaction with relationships at work
27-StandardHours: Standard hours of work
28-StockOptionLevel: Stock option level
29-TotalWorkingYears: Total years of work experience
30-TrainingTimesLastYear: Training times in the last year
31-WorkLifeBalance: Work-life balance rating
31-YearsAtCompany: Number of years at the company
32-YearsInCurrentRole: Number of years in the current role
33-YearsSinceLastPromotion: Years since the last promotion
34-YearsWithCurrManager: Years with the current manager

Analysis

Attrition Rates

Attrition Rate: Employees who stayed (Attrition = 'No') had an average attrition rate of 83.9%, while those who left (Attrition = 'Yes') had an average attrition rate of 16.1%.

Key Findings
Monthly Income: Employees who stayed had a higher average monthly income (Rs6,833) compared to those who left (Rs4,787).
Distance from Home: Employees who left had a greater average distance from home (10.63 km) than those who stayed (8.92 km).
Job Satisfaction: Employees who stayed reported higher job satisfaction (2.78) compared to those who left (2.47).
Environment Satisfaction: Employees who stayed reported higher environment satisfaction (2.77) compared to those who left (2.46).
Overtime: Employees who worked overtime had a significantly higher attrition rate (30.5%) compared to those who did not work overtime (10.4%).

Visualizations
Bar Charts: Comparing attrition rates by job role, average years at the company, and job satisfaction levels.
Box Plots: Showing the distribution of DistanceFromHome, YearsSinceLastPromotion, and TotalWorkingYears grouped by attrition.
Violin Plots: Comparing MonthlyIncome and TotalWorkingYears between employees who stayed and those who left.
Heatmaps: Displaying job level vs. attrition rates.

Conclusion
The analysis highlights several factors influencing employee attrition, including income levels, job satisfaction, and overtime. Understanding these factors can help organizations develop targeted strategies to improve employee retention and satisfaction.

Dependencies
pandas
numpy
matplotlib
seaborn

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Data Source: Kaggle dataset: https://www.kaggle.com/datasets/patelprashant/employee-attrition
