Marketing Analysis
==================

# Dataset
Dataset with results from previous marketing campaigns and customer data: https://www.kaggle.com/datasets/jackdaoud/marketing-data

[EDA](eda.ipynb) contains a Exploratory Data Analysis.

[Customer Segmentation](client_segmentation.ipynb) contains customer segmentation. K-Means was used to find the most similar clients, resulting in 7 different groups.

[Model Building](model_building.ipynb) contains the process of building a model to predict if a customer is likely to accept a future marketing campaigns or not. We found that LGBM (Light Gradient-Boosting Machine) had the best results, followed closely by Logistic Regression.