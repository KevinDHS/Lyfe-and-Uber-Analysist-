# Lyfe and Uber Analysist

## Background

Analyze the online taxi fares between Lyft and Uber using a linear regression model. Since no one has yet analyzed the pricing criteria between these two taxi services using a linear regression model, I decided to make a prediction estimate of the fares for both services.

## Problem Statement

The goal is to build a machine learning model that can perform an analysis and develop a simple linear regression model based on the provided dataset. This model will evaluate how the fares of these taxis vary with all the created features.

The model will be evaluated using the Mean Absolute Error (MAE) loss function.

## Methods Used

The analysis utilized various methods including:

1. Exploratory Data Analysis (EDA): To understand the characteristics and patterns in the data.

2. Data Visualization: To visually represent the data and identify trends, distributions, and relationships.

3. Linear Regression Modeling: To build predictive models and analyze the relationships between variables.

4. Model Evaluation: Using metrics such as Mean Absolute Error (MAE) and R2 Score to assess model performance.

5. Recommendations for Improvement: Suggested enhancements to further improve the model's performance and efficiency.

By employing these methods, a comprehensive analysis of the data and model performance was conducted, leading to insights and recommendations for further refinement.

## Technologies
1. Python
2. Pandas
3. Scikit-Learn
4. phik
5. pickle
6. matplotlib

---

## Findings

## Model Analysis

Based on the Mean Absolute Error (MAE) and R2 Score values obtained, the model's performance is as follows:

1. **Mean Absolute Error (MAE)**:
   * Train Set: 1.74
   * Test Set: 1.78
   MAE is an evaluation metric that measures the average absolute difference between predictions and actual values. A lower MAE indicates better model performance. In this case, the low MAE values indicate that the model tends to make accurate predictions, both for the training and test data.

2. **R2 Score**:
   * Train Set: 0.92
   * Test Set: 0.92
   R2 Score measures how well the variability of the target is explained by the features in the model. The R2 Score ranges from 0 to 1, where values closer to 1 indicate a better model in explaining data variability. In this case, the high R2 Score values indicate that the model has a good ability to explain price variability.

Based on these results, the regression model appears to have good performance with low MAE values and high R2 Score values for both the training and test data. This suggests that the model is capable of providing accurate predictions and has a good ability to explain price variations. However, make sure to validate and test the model with a larger and more diverse dataset to ensure the reliability and generalization of the model.

## Advantages & Disadvantages

### Advantages of Regression Model:
1. Clear understanding of the relationship between variables.
2. Stable and consistent predictions for new data if the data representation is good.
3. Can identify variables that have a significant impact on the target variable.

### Disadvantages of Regression Model:
1. The model assumes a linear relationship between variables, which may not always be the case.
2. Vulnerable to disruption by outliers, which can affect prediction accuracy.
3. Requires conversion of categorical variables into numerical form, which can lead to information loss or bias.

## Overall Analysis

In the overall analysis, the created regression model demonstrates good performance with low MAE and high R2 Score for both the training and test data. However, there are still some areas that need improvement to make the model better and more efficient in its program execution.