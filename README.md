# Predicting-usage-in-steel-industry-using-ML

## Table of Contents

- [Project Overview](project-overview)
- [Data Source](data-source)
- [Major steps followed](major-steps-followed)
- [Insights and Findings](insights-and-findings)
- [Conclusion and further scope](conclusion-and-further-scope)


### Project Overview

This project looks into the application and testing of machine learning techniques using the CRISP-DM methodology. In this project, I have applied two machine-learning models on a steel industry dataset. The steel industry data allows us to compare the performance of regression and classification and even understand how features influence relationships and impacts by outliers.

![ml_steel_industry](https://github.com/user-attachments/assets/cdcf0b50-68db-440a-aec7-483e8c7c0262)

The Linear Regression model was evaluated on the steel industry dataset using three major metrics, Root Mean Squared Error (RMSE), R Squared (R2) Score, and Mean Absolute Percentage Error (MAPE). Whereas, the KNN regression model is evaluated on the steel industry data set, for its predictive accuracy for continuous target variables.


### Data Source

I've taken this dataset from Kaggle. If you want to follow along, I'm sharing the link to the dataset below:

[https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?resource=download](https://www.kaggle.com/datasets/csafrit2/steel-industry-energy-consumption)


### Major steps followed

1. Loading the dataset and converting it into a Python Dataframe.
2. Data cleaning, preprocessing, and normalization.
3. Exploratory Data Analysis
4. Checking the data spread in major features of the dataset.
5. Checking for outliers using boxplots.
6. Splitting the dataset into training and testing splits
7. Applying the linear regression and KNN models.
8. Evaluating the model performances.
9. Analyzing the actual vs the predicted model performances.



Preview of Actual vs Predicted results from this project:

![final_output](https://github.com/user-attachments/assets/e43f574f-fcda-4445-92cd-5ad1b5589f56)



### Insights and Findings

1. The linear regression model’s RMSE came out to be as low as 0.126 which shows an average deviation of the predicted values from the actual values is almost very low. This shows the model's ability to make correct and accurate predictions, with a high R2 score of 0.984.
2. A MAPE score of 16.94% reflects the average error percentage in the predictions of the model. Although it shows some level of variability or instability in the accuracy of predictions, the model still remains acceptable given its high R2 score and low RMSE.
3. The model obtained an RMSE of 0.40 and an R2 score of 0. 82 with a MAPE of 47.20%. The RMSE, R2, and MAPE show moderate predictive capability of the model, with an R 2 score indicating that approximately 82 % of the variance in the target variable is explained by the features.
4. KNN is sensitive to the number of neighbors (k) during parameter tuning. Increasing k improved stability but slightly reduced accuracy. The large MAPE suggests the presence of outliers or highly variable target values that require further refinement of preprocessing steps or alternative regression techniques for comparison.



### Conclusion and further scope

- Linear Regression was superior for the regression tasks on the steel industry data set with great accuracy and robust performance measures.
- KNN regression exhibited fair predictability, although it showed sensitivity to its parameter settings, thus calling for further tuning.
- Additionally, hyperparameter optimization using grid or random search techniques can be implemented to enhance model performance further.
- More extensive evaluation incorporating more datasets and broader metrics, such as explainability and resource efficiency, is needed to understand model applicability.
