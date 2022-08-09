Steps for Linear Regression
* Data Understanding
* EDA
    * Handle data types - Assign proper data types according to column definition
    * Identify obviously unnecessary columns and drop
    * Map flags to numbers - For linear models
    * Check distributions of categorical variables - Bar charts
        * Identifies variables with high skew - Decide whether to keep or drop
    * Check distributions of categorical variables - Box plots
        * Finds outliers
    * Create dummy variables for categorical columns - For linear models
* Train-test split
* Scaling
* Build model
    * sklearn.LinearRegression
    * statsmodels.OLS
    * Eliminate features with RFE
    * Drop variables with high VIF/high p-value
* Evaluate model
    * Perform predictions on the test data
    * Calculate R-squared based on predictions