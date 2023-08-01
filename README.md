# Parkinson's Disease Detection with Voice Measurements

## Overview
In this project, I aimed to predict Parkinson's Disease status using several voice measurements from a dataset. The goal was to build an optimal model by experimenting with feature selection techniques, classifiers, and hyperparameters.

## Dataset
The dataset used for this analysis contains voice measurements of individuals, including healthy individuals and Parkinson's Disease patients. It includes various voice-related features that can help in predicting the disease status.

## Methodology
1. Data Preprocessing: The dataset was cleaned and preprocessed to handle any missing values or outliers.
2. Feature Selection: I explored different feature selection techniques to identify the most relevant voice measurements for building the model.
3. Model Building: After selecting the features, I trained and tested multiple classifiers, including K-Nearest Neighbors, Decision Trees, and Random Forests.
4. Hyperparameter Tuning: To optimize the model's performance, I performed hyperparameter tuning using techniques like grid search with cross-validation.
5. Model Evaluation: I evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## Results
The final model achieved an overall accuracy of approximately 91%. It correctly predicted 50 out of 53 positive cases (Parkinson's Disease patients) and 13 out of 15 negative cases (healthy individuals).

## Limitations and Future Improvements
1. Limited Dataset: The dataset used for this analysis is relatively small. Obtaining a larger dataset could improve the model's performance and generalizability.
2. Feature Engineering: Further exploration of feature engineering techniques may enhance the model's predictive capabilities.
3. Alternative Algorithms: Exploring other classification algorithms, such as Support Vector Machines or Gradient Boosting, may lead to better results.
4. Interpretability: Investigating the relationships between voice measurements and Parkinson's Disease can provide valuable insights.

## Conclusion
This analysis presents a promising starting point for predicting Parkinson's Disease using voice measurements. Further improvements and exploration of different methodologies could lead to more accurate and reliable models for early detection and diagnosis of the disease. The insights gained from this project can contribute to advancements in the field of medical data analysis and contribute to better healthcare outcomes.
