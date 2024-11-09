# Bank Loan Performance Analysis

## Objective
This project focuses on building an interactive tool using Power BI to analyze and visualize borrower behavior and loan performance. The goal is to extract actionable insights that help banks make informed decisions regarding loan strategies, customer behavior, and overall financial performance.

## Project Overview
In this project, I created a comprehensive Power BI dashboard to analyze borrower profiles, loan characteristics, and loan performance trends. By leveraging Power BI’s data modeling and visualization capabilities, I was able to uncover key insights and provide recommendations to optimize the bank’s lending operations.

### Key Features:
- **Data Source**: Loan performance dataset (sourced from Kaggle)
- **Tools Used**: Power BI, Power Query, DAX
- **Focus Areas**: Borrower profile analysis, loan performance, home ownership, delinquencies, and loan purpose

---

## Data Preparation
### 1. Data Collection:
- Extracted the dataset from **Kaggle API**.
- Imported the dataset into Power BI and utilized **Power Query** for data transformation and cleaning.

### 2. Data Cleaning:
- Handled missing values (e.g., converting `'0 Years'` to meaningful values).
- Standardized date formats to ensure consistent data structure.

---

## Data Modeling
- Created relationships between tables using **Loan ID** as the key identifier to establish cardinality, allowing for accurate aggregation of data.
- This ensured that the dashboard could analyze data across various dimensions (e.g., borrower profiles, loan amounts, delinquency status).

---

## Data Visualization
### 1. Visualizations and Reports:
- **Borrower Profile Analysis**:
  - Developed tree maps, line charts, and bar charts to explore loan amounts by home ownership, delinquencies, and performance trends over time.
  - Created slicers and filters to allow users to drill down into specific data segments, such as by loan type, term, or region.
  
- **Loan Performance Analysis**:
  - Used Power BI’s **DAX** language to calculate key metrics such as:
    - **Total non-verified borrowers**.
    - **Fully paid loan percentage**.
  
### 2. Key Visualizations:
- **Tree Map**: Showed average loan amount by purpose, allowing a quick comparison of different loan categories.
- **Line Chart**: Displayed performance trends over time, illustrating the relationship between loan funding and repayments.
- **Bar Chart**: Highlighted delinquency rates based on home ownership status.

---

## Insights and Analysis
### 1. Key Findings:
- **Home Ownership & Delinquencies**: Borrowers with **mortgages** tend to have the highest loan amounts but also exhibit higher delinquency rates.
- **Funding vs. Repayments**: Initially, **funding amounts** were significantly higher than repayments, but over time, this trend stabilized.
- **Loan Performance**: A significant portion of loans are **fully paid**, indicating positive performance in the bank’s lending portfolio.
- **Small Business Loans**: Small businesses have the highest average loan amounts, reflecting the bank’s support for **MSMEs**.
- **Long-Term Loans**: While **long-term loans** have higher interest rates, they are less popular among borrowers.

### 2. Recommendations:
- **Enhance Verification**: A small portion of borrowers are **unverified**—improving verification processes can reduce default risks.
- **Interest Rate Adjustments**: Adjusting interest rates could encourage more borrowers to opt for **long-term loans**, increasing the bank’s revenue.
- **Early Intervention Strategies**: Implement strategies to identify potential loan defaults early, especially for borrowers with higher delinquencies.

---

## Conclusion
This project demonstrated how data visualization can make complex financial data accessible to decision-makers and drive actionable insights. By analyzing borrower profiles and loan performance, the bank can enhance its strategies in several areas:
1. **Verification Process**: Improve borrower verification to reduce risk.
2. **Interest Rates**: Adjust interest rates to promote long-term loans.
3. **Loan Default Management**: Implement early intervention strategies to mitigate potential defaults.

### Future Enhancements:
- **Predictive Analytics**: Incorporate predictive models to forecast delinquency rates and identify at-risk borrowers.
- **External Data Integration**: Integrate external economic data (e.g., inflation rates, unemployment) to provide more context and enhance loan performance analysis.

---

## Key Power BI Techniques:
- **Data Cleaning and Transformation**: Used Power Query to clean and structure the data for analysis.
- **DAX Calculations**: Implemented DAX for key performance metrics like total non-verified borrowers and fully paid loan percentages.
- **Interactive Visualizations**: Designed intuitive visualizations with filters and slicers for deeper insights.

---

## Project Resources
- **[Borrower Profile Analysis Report](https://github.com/vignesh4005/Power_BI_Bank_Loan_Performance_Analysis/blob/main/Bank%20Loan%20Performance%20Analysis/Borrower%20Profile%20Analysis.png)** <!-- Replace with actual link -->
- **[Loan Performance Report](https://github.com/vignesh4005/Power_BI_Bank_Loan_Performance_Analysis/blob/main/Bank%20Loan%20Performance%20Analysis/Loan%20Performance%20Analysis.png)** <!-- Replace with actual link -->
- [Project Presentation](https://github.com/vignesh4005/Bank_Loan_Performance_Analysis/blob/main/Bank%20Loan%20Performance%20Analysis%20Summary.pdf) <!-- Replace with actual link -->
