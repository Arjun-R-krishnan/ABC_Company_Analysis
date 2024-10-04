# ABC_Company_Analysis



This project is an in-depth analysis of employee data from ABC Company, aimed at exploring key workforce trends, salary distributions, and age-related dynamics. The dataset consists of **458 rows** and **9 columns**, covering aspects such as age, salary, team, and position of employees within the company.

## Project Overview

### 1. **Data Preprocessing**
   - **Loading the Dataset**: The dataset was loaded and inspected to understand the structure and ensure there were no missing values.
   - **Random Data Generation**: A column for `Height` was generated randomly for all employees to complement the analysis.
   - **In the preprocessing phase, null values in the "College" column were replaced with "Unknown" to ensure data completeness.                 Additionally, null values in the "Salary" column were removed, as the number of missing entries was negligible and did not 
       significantly impact the overall analysis.
### 2. **Analysis Tasks**
   The following tasks were performed to gain insights into the data:
   
   - **Employee Count by Team**: The number of employees was calculated for each team in the company, showing how different departments or teams are structured.
   - **Employee Count by Position**: The workforce distribution was examined by position (e.g., center, forward), revealing the importance of various roles.
   - **Employee Count by Age Group**: Employees were categorized into age groups (18-24, 25-29, etc.) to analyze the distribution of employees by age.
   - **Salary Distribution by Team and Position**: Analyzed how salaries are distributed across different teams and positions to identify any patterns or trends.
   - **Correlation Analysis**: The correlation between age and salary was calculated to explore the relationship between employee age and salary levels.

### 3. **Graphical Representations**
   Several visualizations were created to enhance the analysis, including:
   - **Bar Charts**: Showed the distribution of employees by team and position.
   - **Heatmaps**: Visualized the correlation between age and salary.
   - **Salary by Team**: Highlighted differences in financial investment across teams.
   - **Salary by Position**: Illustrated which positions command the highest salaries.

### 4. **Insights Gained**
   - **Team Structure**: The analysis revealed how each team’s employee count varies, with some teams having more staff to support their operations.
   - **Position Analysis**: The dataset highlighted the significance of roles like shooting guard and power forward in the company’s workforce.
   - **Age Distribution**: The company has a high concentration of employees in their twenties, indicating a younger workforce with fewer older employees.
   - **Salary Distribution**: Certain teams invest significantly more in salaries, while others may focus on cost management or talent development.
   - **Position Salaries**: Positions such as center and point guard command the highest salaries, reflecting their pivotal roles in team dynamics.
   - **Age-Salary Correlation**: A weak positive correlation between age and salary was found, suggesting that other factors like experience or performance likely influence salary more than age.

## Additional Information

- **Tools Used**: Python, Pandas, NumPy, Matplotlib
- **Data Source**: Proprietary dataset from ABC Company
- **Dependencies**: Ensure all necessary libraries are installed, such as `pandas`, `numpy`, and `matplotlib`.

## Setup and Usage

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook for a detailed step-by-step analysis:
   ```bash
   jupyter notebook ABC_Company_Analysis.ipynb
   ```

---

This README provides a clear overview of the dataset, preprocessing steps, and insights gained. You can adjust the wording or include additional sections as needed for your project!
