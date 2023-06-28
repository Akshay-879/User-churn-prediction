# User churn prediction

## Description:

This project involves analyzing a dataset related to telecom users to predict customer churn. The dataset consists of various features such as customer ID, gender, senior citizenship, partner status, dependents, tenure, phone service, internet service, online security, online backup, device protection, tech support, streaming TV, streaming movies, contract type, paperless billing, payment method, monthly charges, total charges, and churn status.

The project begins with exploratory data analysis (EDA) to gain insights into the dataset. The EDA involves examining the distribution and relationships between different variables. Some key findings from the EDA include:

The gender of the customer does not have a significant impact on churn.
Senior citizens tend to churn more than younger people.
Customers with fiber optic internet service have a higher probability of terminating their services.
Customers with yearly plans have a lower probability of churning compared to monthly plans.
Customers with fiber optic connections tend not to take device protection and tech support, which may contribute to their higher churn rate.
Customers with no online security and no online backup have a higher probability of terminating their services.
The next step in the project is data preprocessing. Numeric variables are separated from categorical variables, and label encoding is applied to the categorical variables. The dataset is then transformed by combining the numeric and encoded categorical variables. Variables with high collinearity are dropped to avoid multicollinearity issues.

The dataset is imbalanced, with a higher number of non-churned customers compared to churned customers. To address this, the data is balanced using the Synthetic Minority Over-sampling Technique (SMOTE). SMOTE generates synthetic samples for the minority class (churned customers) to achieve a balanced dataset.

The dataset is then split into training and testing sets, and the features are scaled using standardization. A support vector machine (SVM) classifier with a linear kernel is trained on the training data. The classifier is used to predict churn on the testing data, and the performance is evaluated using a confusion matrix and accuracy score.

Overall, this project aims to develop a churn prediction model using the telecom user dataset. The project involves EDA, data preprocessing, balancing the dataset, feature scaling, and training an SVM classifier. The outcome of the project is a churn prediction model that can assist in identifying customers who are likely to terminate their services, allowing companies to take proactive measures to retain those customers.

### Machine Learning Models:
1. Support Vector Classifier
2. Random Forrest Classifier
3. Artificial Neural Network

### Libraries:
1. Numpy
2. Pandas
3. Sklearn
4. Keras
4. Tensorflow
