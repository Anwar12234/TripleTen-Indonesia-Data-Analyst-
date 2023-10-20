# Analysis of Borrower Default Risk

This project is part of an assignment to evaluate the credit risk of prospective customers at a bank. The purpose of this analysis is to understand how factors such as marital status, number of children, income, and loan purpose can influence the probability of loan default.

## Data

The data used in this project consists of the following information:

- `children`: Number of children in the family.
- `days_employed`: How long the borrower has been employed (in days).
- `dob_years`: Age of the borrower (in years).
- `education`: Education level of the borrower.
- `education_id`: Identifier for the borrower's education level.
- `family_status`: Marital status of the borrower.
- `family_status_id`: Identifier for the borrower's marital status.
- `gender`: Gender of the borrower.
- `income_type`: Type of income of the borrower.
- `debt`: Whether the borrower has ever defaulted on a loan.
- `total_income`: Monthly income of the borrower.
- `purpose`: Purpose of taking the loan.

## Analysis Process

The data analysis process was conducted in several steps:

1. **Data Exploration**: Reviewing general dataset information, identifying missing values, and examining the first few rows of data.

2. **Data Transformation**: Resolving duplicate values, addressing unrealistic values in the `children` column, converting negative values in `days_employed` to positive, and removing data with unrealistic `dob_years`.

3. **Handling Missing Data**: Filling in missing values in the `total_income` and `days_employed` columns using appropriate methods, such as median based on age groups or income types.

4. **Data Categorization**: Categorizing certain columns, such as `children`, `total_income`, and `purpose`, to facilitate hypothesis analysis.

5. **Hypothesis Analysis**: Analyzing the relationship between various factors such as having children, family status, income level, and loan purpose with the probability of loan default.

## Results

The analysis results indicate that:

- There is no significant correlation between having or not having children and the probability of loan default.
- Family status also does not correlate with the probability of loan default.
- Income level does not affect the probability of loan default.
- The purpose of the loan also does not have a significant impact on the probability of loan default.

## Conclusion

From this analysis, it can be concluded that factors such as having children, family status, income level, and loan purpose do not have a significant impact on the probability of loan default. Therefore, in credit assessment, these factors may not be the primary determining factors in assessing a borrower's ability to repay a loan.

This project utilized the Python programming language and the pandas library for data analysis. The findings from this analysis can assist the credit team in making better-informed decisions when assessing the credit risk of prospective customers.

If you are interested in exploring further details about this analysis, please check the complete code and data in the project directory.
