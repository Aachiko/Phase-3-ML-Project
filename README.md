# SyriaTel Customer Churn Prediction: Sales and Marketing Approach

## Overview
SyriaTel, a telecommunications company, faces the challenge of customer churn. To address this, we’ve developed a predictive model using machine learning. Our focus is on sales and marketing strategies to retain valuable customers. In this README, we’ll cover the business context, data understanding, model evaluation, and recommendations.

## Business Understanding
Company: SyriaTel
Objective: Reduce churn, maintain revenue, and enhance customer satisfaction.
Importance of Churn Prediction:
Early identification of potential churners allows targeted retention efforts.
Proactive measures prevent revenue loss and improve customer experience.

## Data Understanding
Dataset has 3333 rows and 2
Features:  'account length', 'area code', 'international plan', 'voice mail plan', 'number vmail messages', 'total day minutes', 'total day calls', 'total day charge', 'total eve minutes', 'total eve calls', 'total eve charge', 'total night minutes', 'total night calls', 'total night charge', 'total intl minutes', 'total intl calls', 'total intl charge', 'customer service calls').
Target variable: Churn (1 for churn, 0 for non-churn).



## Models Evaluated
We explored three models:

Logistic Regression:
Adjusted Recall: 0.9010
Reasons:
Interpretable coefficients help identify influential features.
Linear relationship assumption aligns with business understanding.

Decision Tree:
Adjusted Recall: 0.7624
Reasons:
Non-linear relationships captured by tree structure.
Useful for segmenting customers based on risk.

Random Forest (not provided in user input):
Reasons:
Ensemble of decision trees.
Improved robustness and generalization.

## Recommendations
-High Recall Strategy:
Leverage logistic regression’s high recall to identify at-risk customers.
Implement targeted retention efforts (personalized offers, loyalty programs).
-Feature Insights:
Analyze logistic regression coefficients to understand key churn drivers.
Focus on improving those areas (e.g., customer service, pricing).
-Customer Segmentation:
Use decision tree segments for tailored marketing strategies.
Target promotions based on churn risk.
-Feedback Loop:
Continuously monitor model performance.
Collect feedback from sales and marketing teams.
Refine models based on real-world outcomes.

## Conclusion
This project equips SyriaTel with actionable insights to reduce churn and enhance customer retention. Collaboration between data science, sales, and marketing teams is crucial for success.


