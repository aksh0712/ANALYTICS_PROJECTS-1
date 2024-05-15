DATA-SCIENCE_PROJECTS-1
Predict Credit Consumption of Customer for Leading Bank.

BUSINESS OBJECTIVE: The data from a credit card processor shows the consumer types and their business spending behaviors. Therefore, companies can develop the marketing campaigns that directly address consumers’ behavior. In return, this helps to make better sales and the revenue undoubtedly grows greater sales.

Solution Data Pipelines.
1) crucial Import packages, then read respective data files, and after that merge all data files into one file by using pd.merge().
2) Generate file report for general analysis like No. of missing values, correlated values, residuals so on.
3) Now perform Exploratory data analysis - Process data based on the data audit report, and identify a relationship between the target variable and other numerical variables.
4) Drop the variable based on the data audit report - drop the variable whose value is near zero variance, highly missing, highly correlated, and using business logic.
5) Now generate a statistical summary using describe() of the data frame.
6) After statistical analysis now it's time to separate continuous and categorical data.
7) To determine data skewness we need to check the normality of the target variable, to determine the correlation of each variable with the target variable we need to generate Heatmap.
8) It is good practice to split the data into train & test datasets, to avoid the problem of Overfitting, this split is crucial.
9) A Feature Engineering Process is applied for feature selection and variable reduction.
10) After this we have to check the Multicolinearity using VIF ie. Variance Inflation Factor.
11) Now we have built a Model using OLS ie. Ordinary Least Square method.
12) Now it's time to determine various metrics on train & test datasets to check for Error Distribution, then save the model using the Pickle object with this we complete the Model Building Process.
13) Now to optimize the operations to improve the performance of Credit Card Consumption we need to apply different machine learning algorithms such as Random Forest, XGBoost, and SVM.
