This project features machine learning methodologies aimed at anticipating Customer Churn and enhancing retention strategies within the telecom industry. 

Utilizing a dataset from a telecom company in California, USA, comprising demographic and service purchase behavior data for 7043 customers, it showcases the application of feature engineering techniques like Recursive Feature Elimination (RFE), SelectKBest, and Synthetic Minority Over-sampling Technique (SMOTE) to improve the model's performance. 

The model selection was conducted using the Area Under the Receiver Operating Characteristic Curve (ROC AUC) score, which evaluates the model's ability to identify instances of churn, alongside other evaluation metrics such as Precision, Recall, F1 Score, test accuracy, and training accuracy to check for overfitting. Validation and deployment are also utilized to enhance churn prediction accuracy and translate predictions into actionable strategies.


In the experimentation phase, three machine learning models Logistic Regression, Support Vector Machine (SVM), and Random Forest were tested with subsets of the dataset. 

This iterative approach progresses from simpler to more complex models, incorporating additional features. 

After completing all experiments, the best model was determined by averaging all evaluation matrices where Logistic Regression emerged as the superior model for capturing churn dynamics, especially when incorporating more features and leveraging feature selection and class imbalance techniques.



The success of Logistic Regression in capturing churn dynamics reaffirms the effectiveness of simpler models. Logistic Regression's ability to handle nonlinear relationships between features and the target variable makes it well-suited for capturing the intricate dynamics of churn behavior. Additionally, its simplicity facilitates easier interpretation of results, enabling actionable insights to be extracted more readily.



Not confined to our Jupyter notebook, the model seamlessly integrates with existing systems and software utilized across the telecom business, including Customer Relationship Management (CRM) systems. This integration can be facilitated through APIs or database connections.
