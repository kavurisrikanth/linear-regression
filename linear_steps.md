Steps for Linear Regression
1. Data Understanding
2. EDA
    2.1. Handle data types - Assign proper data types according to column definition
    2.2. Identify obviously unnecessary columns and drop
    2.3. Map flags to numbers - For linear models
    2.4. Check distributions of categorical variables - Bar charts
        2.4.1. Identifies variables with high skew - Decide whether to keep or drop
    2.5. Check distributions of categorical variables - Box plots
        2.5.1 Finds outliers
    2.6. Create dummy variables for categorical columns - For linear models
3. Train-test split
4. Scaling
5. Build model
    sklearn.LinearRegression
    statsmodels.OLS
    Eliminate features with RFE
    Drop variables with high VIF/high p-value
6. Evaluate model
    Perform predictions on the test data
    Calculate R-squared based on predictions