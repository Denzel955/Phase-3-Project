Customer Churn Analysis for Syriatel

Problem Statement
• Churn: When customers discontinue service
• High churn rate leads to revenue loss
• Syriatel seeks to address increasing churn

Success Criteria
• Identify 5+ key features linked to churn
• Classifier model with ≥90% accuracy, ≥75% precision
• Actionable insights to reduce churn

Data Understanding
• Sourced from Kaggle: 3,333 rows, 21 columns
• Customer data: state, account length, plans, call metrics, churn flag

Feature Details (Part 1)
• International & voicemail plans
• Call minutes and charges (day/evening/night/int’l)
• Customer service calls
• Churn (True/False)

Data Preparation
• Checked for duplicates, missing & null values
• No issues found; clean dataset

Categorical Variable Insights
• Most customers retained; churn still impactful
• Majority resolved issues in 4 calls
• Only 1/3 have voicemail plan
• Int’l plans are rare—domestic focus

Numeric Variable Insights
• Call usage shows normal distribution
• Charges align with usage—no pricing anomalies

Correlation Analysis
• Charges highly correlate with minutes
• Validates appropriate pricing strategy

Customer Service & Churn
• Churned customers made more service calls
• Indicates unresolved issues influenced churn

Model Evaluation

Model: Logistic Regression | RF Classifier | Decision Tree

Accuracy: 84% | 95% | 93%
Precision: 11% | 74% | 69%
F1-Score: 19% | 83% | 76%

Model Recommendation

• Random Forest performed best
• High precision & reliability
• Logistic regression not suitable

Conclusion

• Use Random Forest for churn prediction
• Monitor customer service interaction

Recommendations

• Implement retention strategies
• Focus on resolving customer issues
• Use model to track retention efforts


