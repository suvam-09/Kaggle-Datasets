# BOSTON HOUSE PRICE PREDICTION
The project highlights an applied usage of machine learning focused on predicting house prices. The dataset used in this project comes from the UCI Machine Learning Repository. This data was collected in 1978 and each of the 506 entries represents aggregate information about 14 features of homes from various suburbs located in Boston. The dataset is available on Kaggle. Our goal is to develop a model that has the capacity of predicting the value of houses.

Various machine learning models such as Linear Regression, Lasso Regression, ElasticNet Regression & Xtreme Gradient Boosting Regression have been implemented over the preprocessed data to evaluate the model with the highest accuracy. Accuracy for the model are defined using performance metrics which includes calculating various types of error, the goodness of fit, or some other useful measurement. For this project I have used the coefficient of determination (R²) to quantify the model’s performance. The *coefficient of determination* for a model is a useful statistic in regression analysis as it often describes how "good" that model is at making predictions. Please refer below table with regards to the performance metrics for each of the machine learning models that have been implemented in the project:




Click here to run the application live on server

## Feature Observation
Data Science is the process of making some assumptions and hypothesis on the data and testing them by performing some tasks Initially we could make the following intuitive assumptions for few of the features:
- Houses with more rooms (higher 'RM' value) will worth more. Usually houses with more rooms are bigger and can fit more people, so it is reasonable that they cost more money. They are directly proportional variables.
- Neighborhoods with more lower class workers (higher 'LSTAT' value) will worth less. If the percentage of lower working class people is higher, it is likely that they have low purchasing power and therefore, they houses will cost less. They are inversely proportional variables.
- Neighborhoods with more students to teachers ratio (higher 'PTRATIO' value) will be worth less. If the percentage of students to teachers ratio people is higher, it is likely that in the neighborhood there are less schools, this could be because there is less tax income which could be because in that neighborhood people earn less money. If people earn less money it is likely that their houses are worth less. They are inversely proportional variables.

We’ll find out if these assumptions are correct through the project.

The features can be summarized as follows:
- CRIM: This is the per capita crime rate by town
- ZN: This is the proportion of residential land zoned for lots larger than 25,000 sq.ft.
- INDUS: This is the proportion of non-retail business acres per town.
- CHAS: This is the Charles River dummy variable (this is equal to 1 if tract bounds river; 0 otherwise)
- NOX: This is the nitric oxides concentration (parts per 10 million)
- RM: This is the average number of rooms per dwelling
- AGE: This is the proportion of owner-occupied units built prior to 1940
- DIS: This is the weighted distances to five Boston employment centers
- RAD: This is the index of accessibility to radial highways
- TAX: This is the full-value property-tax rate per $10,000
- PTRATIO: This is the pupil-teacher ratio by town
- B: This is calculated as 1000(Bk — 0.63)², where Bk is the proportion of people of African-American descent by town
- LSTAT: This is the percentage lower status of the population
- MEDV: This is the median value of owner-occupied homes in $1000s