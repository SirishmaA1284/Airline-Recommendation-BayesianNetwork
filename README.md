# Airline Recommendation System Using Bayesian Networks

This project contains the implementation of an **Airline Recommendation System** using **Bayesian Networks** to analyze customer feedback and predict recommendations. This project addresses the challenges of analyzing complex interdependencies in feedback data and provides actionable insights for improving airline services.

## Key Features
- **Bayesian Network Model:** Captures dependencies between features like overall rating, cabin staff rating, and value-for-money rating to predict customer recommendations.
- **Data Preprocessing:** Handles missing values, encodes categorical variables, and performs feature selection using correlation analysis for accurate predictions.
- **High Accuracy:** Achieved 90.99% test accuracy with detailed insights using a confusion matrix.
- **Interpretable Results:** Provides insights into key factors like seat comfort and inflight entertainment that influence recommendations.

## Objectives
- Build a probabilistic model to predict airline recommendations.
- Identify critical factors impacting customer satisfaction.
- Offer actionable insights for service improvements.

## Technical Details
- **Dataset:** Contains customer reviews and ratings, including features like seat comfort, food and beverages, inflight entertainment, and the "recommended" target variable.
- **Model:** Bayesian Network trained using Maximum Likelihood Estimation (MLE) to compute Conditional Probability Distributions (CPDs).
- **Evaluation:** Model performance evaluated using accuracy and confusion matrix for interpretability.

## Methodology
- Preprocessed data to handle missing values, encode categorical variables, and normalize ratings.
- Constructed a Bayesian Network using domain knowledge to define dependencies among features.
- Trained the network with MLE and tested predictions on unseen data.

## Results
- **Accuracy:** Achieved a high test accuracy of 90.99%.
- **Key Influencing Factors:** Overall rating, value-for-money rating, and cabin staff rating were the strongest predictors of customer recommendations.
- **Practical Implications:** Provides interpretable insights to airlines for targeted service improvements.

## Future Enhancements
- Incorporate additional features like ticket pricing and flight duration for improved predictions.
- Deploy the model on cloud platforms for real-time recommendations.
- Add multilingual support and a feedback loop for continuous updates.

