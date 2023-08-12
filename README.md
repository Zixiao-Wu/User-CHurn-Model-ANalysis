# User Churn Model Analysis
This is a project aims to build an user churn analysis model

## Project Purpose¶
The project aims to gain an in-depth understanding of user profiles and behavioral preferences, identify key factors influencing user churn, and utilize algorithms to predict customer visit conversions. This will help in enhancing product design and improving user experience.

## Data Description
The data used in this project represents one week of visit data from Ctrip users. To protect customer privacy, the data has been anonymized, and there may be some discrepancies with actual order quantities, page views, and conversion rates. However, this does not affect the solvability of the problem.

## Case Description
The case involves a classification information application that uses data mining to analyze key factors affecting user churn and understand user behavioral preferences. Based on the analysis, adjustments are made to improve customer retention and enhance customer loyalty. Additionally, the project uses the Random Forest algorithm to predict customer churn.

## Project Content
Explore data distribution and missing values, and perform targeted imputation for missing data. For features with few missing values, use the Random Forest imputation method. Deal with outliers using methods such as 3-sigma rule and boxplots. Encode categorical variables.

Apply variance filtering and F-test to remove some features. Perform Weight of Evidence (WOE) binning for the remaining features. Visualize the binning results for each feature to analyze user behavioral preferences. Further filter features based on the Information Value (IV) of each feature.

Train the Random Forest model, tune and evaluate its performance, and output the final model. Use this model to predict user churn and take actions to retain users. Train the Logistic Regression model for its strong interpretability (feature coefficients) to explain the key factors of user churn. Also try to apply XGBoost in comparison of random forest.

Data source: Wechat Subscriptions "数据STUDIO“

Data description: [Data Introduction](Data_Introduction.xlsx)

Raw Data: [User data](userlostprob.rar)
