# Data Science Project : Customer Churn Prediction for a Cell2Cell Telecom Company

## [Final Data Science Capstone Project as part of Springboard Data Science bootcamp course]
![Churn prediction](https://github.com/thikyi/Telecom-Customer-Churn/blob/main/banner.showcase.png)

## Context
The project aims to tackle customer churn in the telecom industry by developing a predictive model for effective retention strategies.

### Problem Identification
Telecom companies face intense competition, leading to high customer churn rates. This churn not only impacts revenue but also increases the cost of acquiring new customers, which is typically higher than retaining existing ones. A predictive model for customer churn can help in identifying at-risk customers and devising strategies to retain them.

####  Problem Formulation Statement
To develop a predictive model to forecast customer churn for the telecom company. The model will analyze customer behavior and patterns to predict the likelihood of customers discontinuing the service. This model will enable the telecom company to proactively take retention measures, thereby reducing churn rates and enhancing customer satisfaction and loyalty.

####  Criteria for Success
The project success will be measured by:
- the accuracy and reliability of the predictive model in identifying potential churn customers
- the effectiveness of the recommended retention strategies based on the model’s insights.
####  Scope of Solution Space
The scope includes developing a model to predict customer churn based on existing customer data, analyzing behavior patterns, and recommending retention strategies. The solution will focus on actionable insights that can directly impact customer retention strategies.
####  Constraints
The primary constraints include data quality, model accuracy, and the effectiveness of retention strategies. The model will be limited by the available data and may not account for external factors influencing customer decisions.

####  Stakeholders
- Telecom company management and strategy team
- Marketing and customer relations departments
- Data science and analytics teams

## Project Approch

### Data Acquisition
The primary data source is available at: https://www.kaggle.com/datasets/jpacse/datasets-for-churn-telecom

### Solution Overview
[Data Acquisition & Cleaning](https://github.com/thikyi/Telecom-Customer-Churn/blob/main/notebooks/Step1_DataWrangling.ipynb): Acquired from Kaggle, the dataset underwent cleaning and wrangling to set the stage for analysis.

[Exploratory Data Analysis (EDA)](https://github.com/thikyi/Telecom-Customer-Churn/blob/main/notebooks/Step2_EDA.ipynb): Delved into customer demographics and behavior, revealing key churn influencers and preparing data for predictive modeling.

[Pre-processing](https://github.com/thikyi/Telecom-Customer-Churn/blob/main/notebooks/Step3_Preprocessing.ipynb): Segmented customers, engineered features, and prepared the data for model training with a focus on predictive accuracy.

[Modelling](https://github.com/thikyi/Telecom-Customer-Churn/blob/main/notebooks/Step4_Modeling.ipynb): Selected and fine-tuned models, with RandomForestClassifier emerging as the best predictor of customer churn.

[Data Visualisation](https://public.tableau.com/app/profile/thant.thiri.kyi/viz/TelecomChurn_17094319695010/Story1): Visualized predictions and churn risk segments, offering insights into customer behavior and guiding targeted retention strategies.

[Project Reports](https://github.com/thikyi/Telecom-Customer-Churn/tree/main/reports): Reports are prepared.

### Footer Note
All files cannot be uploaded into Github because of size limitation. Full data files processed throughout the project can be found at 
