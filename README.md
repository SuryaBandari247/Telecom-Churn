<a name="readme-top"></a>
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/surya-bandari/)


# Telecom Churn - Classical ML model - Telecom Domain
> In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.


## Table of Contents
* [General Information](#general-information)
* [Steps followed](#Steps)
* [Technologies Used](#technologies-used)
* [Results](#Results)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem statement
> For many incumbent operators, retaining high profitable customers is the number one business goal.
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
In this project, you will analyze customer-level data of a leading telecom firm, and build predictive models to identify customers at high risk of churn.

> It is your job to predict if a customer will churn, given the ~170 columns containing customer behavior, usage patterns, payment patterns, and other features that might be relevant. Your target variable is "churn_probability"

![1621963349834](https://github.com/SuryaBandari247/Telecom-Churn/assets/128714777/6ba4e990-55b7-497f-9701-2b0f60523bdb)


## Steps
* Data Understanding
  * Duplicate check
  * Churn ratio
* Initial sweetviz report
* Missing value imputation
* Date columns
  * Categorical columns
  * Numerical columns
  * Drop columns with more than 70 percent missing data
* Derived columns / feature engineering
  * Combine both incoming and outgoing call activity of months 6/7 and compare with month 8
  * Combine recharge of data and calls of months 6/7 and compare that with month 8
  * Grouping the customers based on AON
  * Drop the columns having less than 2 unique values
* Data visualisation
  * Univariate analysis
  * Bivariate analysis
  * Segmented analysis
* Data preparation & Model Building
  * Dummy variable creation
  * Spliting Data into train and test
  * Outlier treatment - Winsorisation
  * Feature Scaling - Standard scaler
* Model Building
  * Applying PCA
    * Applying Logistic regression on the new Principal components
    * Finding Optimal Cutoff Point - Logistic
    * Evaluation metrics - Logistic
  * Applying Random forest
    * Hypermeter tunning - Random forest
    * Finding Optimal Cutoff Point - Random forest
    * Evaluation metrics - Random forest
  * Applying XBboosting
    * Hypermeter tunning - XGBoosting
    * Finding Optimal Cutoff Point - XGBoosting
    * Evaluation metrics - XGBoosting
* Model selection
  * Comparing all the models
* Select important features from XGB classifer
* weights of features: Implement logistic model on top_imp_features
* Recommendations to Business

## Technologies Used
- Jupyter notebook - version 6.4.12
- Python - version 3.10.0
- Pandas - version 2.0
- Numpy - version 1.24.2
- sklearn - version - 1.2.2
- seaborn - version - 0.12.2

## Results
https://github.com/SuryaBandari247/Telecom-Churn/blob/main/kaggle_result.xlsx
 

## Acknowledgements
- Upgrad
- Google in general

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
## Contact
Created by [@suryabandari247](https://www.linkedin.com/in/surya-bandari/) - feel free to contact me!
