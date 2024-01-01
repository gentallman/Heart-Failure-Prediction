## Heart Failure Prediction Using Machine Learning

This project focuses on leveraging machine learning techniques to predict heart failure, a critical health concern that claims millions of lives annually. By analyzing a dataset obtained from the UCI Machine Learning Repository, we employed various machine learning algorithms, visualization tools, and data analytics techniques to understand patterns and indicators leading to heart failure.

![Dashboard](https://github.com/gentallman/Heart-Failure-Prediction/blob/main/dashboard.png)

### Key Objectives:

- Exploratory Data Analysis (EDA): Investigate relationships between various attributes and their correlation with heart failure.
- Model Development: Implement multiple machine learning models such as Random Forest, Decision Tree, Gradient Boosting, etc., targeting a prediction accuracy range of 80-90%.
- Dashboard Creation: Develop an interactive dashboard to visualize key metrics, trends, and insights related to heart failure prediction, enhancing user understanding and accessibility.
- Model Deployment: Integrate the top-performing model into a user-friendly web application, enabling users to input relevant attributes and obtain heart failure probability predictions.

### Methodology Highlights:

- Data Collection: Acquired a dataset comprising 299 records encompassing 13 attributes pertinent to heart health.
- Data Preprocessing: Ensured data integrity by identifying and managing missing values, with all attributes categorized as 'float64' or 'int64'.
- Exploratory Data Analysis: Leveraged the Plotly library to visualize data relationships, uncover patterns, and derive actionable insights.
- Feature Selection & Model Comparison: Utilized techniques like Confusion Matrix, Precision-Recall Curve, and ROC Curve for feature selection and model evaluation.
- Model Deployment: Constructed a web application using Flask, facilitating users to input attributes and receive heart failure probability estimations.

## Key Findings:

- Identified pivotal predictors of heart failure, including age, ejection fraction, creatinine phosphokinase levels, serum sodium, and comorbid conditions such as diabetes and anemia.
- Achieved an 80% prediction accuracy using the Gradient Boosting Classifier.
- Observed a slight male predominance in heart failure risk and identified lifestyle factors like smoking as potential risk amplifiers.
