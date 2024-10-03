# AMCAT Data Exploratory Data Analysis (EDA) Project

## Project Overview
This project involves performing an exploratory data analysis (EDA) on the AMCAT dataset to uncover patterns and relationships in the data. The objective is to analyze the dataset, clean and manipulate it, and visualize key insights that can assist stakeholders in understanding the employment landscape of engineering graduates.

**Data Source:**  
[Download the dataset](https://github.com/Angad143/EDA-Projects---Analysis-of-AMCAT-Data/blob/main/data.xlsx)

---

## Steps in the Project

### 1. **Introduction**
   The project aims to explore a dataset related to the employment outcomes of engineering graduates. It includes variables related to academic scores, skills, and salary. The goal is to analyze how various factors affect the salary of graduates and provide insights that can guide recruitment and career planning.

### 2. **Data Import**
   - Imported the AMCAT dataset using Python libraries like `pandas` and `numpy`.
   - Performed an initial review of the data structure, size, and basic descriptive statistics to understand the key features of the dataset.

### 3. **Data Cleaning**
   - Handled missing values in various columns by imputing or dropping them based on relevance and data integrity.
   - Replaced placeholder values (e.g., `-1`, `0`) with appropriate null values or meaningful replacements.
   - Ensured consistent formatting for categorical columns such as degree names and specializations.

### 4. **Data Manipulation**
   - Applied transformations to categorical and numerical columns to improve data quality and consistency.
   - Created new features, such as aggregating related columns for better insights and ensuring the data was in the correct format for analysis.
   - Example: Replaced specific degree titles for consistency in the `Specialization` column.

### 5. **Univariate Analysis**
   - **Numerical Variables**: Generated histograms, KDE plots, and boxplots to understand the distribution of scores such as `10percentage`, `12percentage`, and `collegeGPA`. This helped identify outliers and the overall shape of data distributions.
   - **Categorical Variables**: Used count plots to explore the frequency distribution of variables like `Specialization` and `Gender`.

### 6. **Bivariate Analysis**
   - **Numerical vs. Numerical**: Performed correlation analysis using scatter plots and heatmaps to identify relationships between variables like `college GPA` and `Salary`.
   - **Categorical vs. Categorical**: Created stacked bar plots to assess trends in the distribution of specializations by gender.
   - **Numerical vs. Categorical**: Boxplots were used to explore how salary varies across different specializations and gender groups.

### 7. **Key Insights**
   - Found that higher scores in skills like `Logical` and `Quant` are correlated with higher salaries.
   - Observed gender differences in specializations, with males predominantly choosing technical fields like `Electronics & Communication Engineering`, and females more represented in fields like `Biotechnology`.

### 8. **Conclusion**
   - The project uncovered valuable insights into the employment patterns of engineering graduates. The findings can guide recruiters and educational institutions in tailoring recruitment strategies, skill development programs, and career counseling.
   - Additionally, testing a real-world claim about graduate salaries based on academic performance and specialization demonstrated the power of data in decision-making.

---

## How to Run the Project
1. Clone the repository to your local machine.
2. Ensure you have Python and necessary libraries installed (`pandas`, `numpy`, `seaborn`, `matplotlib`).
3. Run the Jupyter notebooks or Python scripts to reproduce the analysis and visualizations.

---

## Research Question

### A) Claim from a Times of India Article

A Times of India article dated January 18, 2019, states:  
**"After doing your Computer Science Engineering, if you take up jobs as a Programming Analyst, Software Engineer, Hardware Engineer, or Associate Engineer, you can earn up to 2.5-3 lakhs as a fresh graduate."**

**Test this claim with the given data:**

**Answer**:  
Based on the data analysis, fresh graduates with a Computer Science & Engineering specialization working as Programming Analysts, Software Engineers, Hardware Engineers, or Associate Engineers earn within the 2.5-3 lakh salary range. The claim from the Times of India article is supported by the data.

---

## **Bonus: Additional Research Question**

### Is it possible for prestigious law firms to hire only graduates with an average GPA of 3.8?

**Scenario**:  
Two colleagues, one employed at a prestigious law firm and the other at a startup legal consultancy, debate the feasibility of maintaining such a high GPA.

- **Prestigious Law Firm**: The firm claims they only hire people with GPAs above 3.5, with an average hire GPA of 3.8.
- **Startup Legal Consultancy**: This firm doubts that it’s possible to maintain such a high average GPA.

**Answer**:  
Yes, it is possible. Prestigious law firms often recruit top graduates, which aligns with their preference for candidates with GPAs above 3.5. Having an average GPA of 3.8 among hires is believable, as these firms target the best students in the market.

### Analysis:

To investigate this claim, we focused on employees with job titles like "programmer analyst," "software engineer," "hardware engineer," and "associate engineer." We conducted hypothesis testing to check whether the average GPA of law graduates hired by the firm indeed exceeded 3.5, and whether the average GPA among hires was 3.8. Using statistical methods, such as calculating p-values and comparing with critical values, we were able to evaluate the firm's claim and found it to be statistically significant. 

--- 

## Conclusion
The AMCAT EDA project helped me build practical data analysis and visualization skills while uncovering meaningful insights from the data. This repository is open for anyone interested in EDA techniques and employment data analysis.
