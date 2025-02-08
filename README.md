# Modelling Car Insurance Claim Outcomes Using R

## Project Background
Insurance companies invest significant time and resources into optimizing pricing models and accurately estimating the likelihood of customer claims. With the emergence of AI, predictive models can be developed to assist insurance companies in predicting whether a customer will file a claim during the policy period.

## Objective of the Project
The objective of this project was to use simple Logistic Regression to identify the single feature that results in the best-performing model, as measured by accuracy.

## Tasks
- **Data Cleaning:** Investigate and clean the dataset to ensure there are no missing values and remove the `id` column.
- **Feature Selection:** Identify the feature with the best predictive performance for a car insurance claim (`outcome`) by creating simple Logistic Regression models (each with a single feature) and assessing their accuracy.
- **Performance Evaluation:** Create a data frame with columns `best_feature` and `best_accuracy`, displaying the feature with the highest accuracy and the corresponding accuracy score.

## Results and Conclusion
The feature that results in the highest accuracy is **`driving_experience`**. When used with the model, it achieves an accuracy score of **78%**.

