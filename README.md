# Credit Score Classification using Supervised Learning
This project involved developing an intelligent system for a global finance company to automate the segregation of individuals into credit score brackets. The goal was to reduce manual efforts and improve efficiency in assessing creditworthiness.

# Problem Statement
The finance company had accumulated a significant amount of data consisting of basic bank details and credit-related information about individuals. The management wanted to leverage this data to build a predictive model capable of accurately categorizing individuals into different credit score categories. The objective was to streamline the decision-making process and enhance the accuracy of credit assessments.

# Supervised Learning
Supervised learning is a machine learning technique where models are trained using labeled examples to make predictions or classifications. In this project, supervised learning was employed to train a model on historical data, where the credit scores of individuals were known. The trained model was then used to predict the credit scores of new, unseen individuals.

# Classification Problems
Classification is a type of supervised learning problem that involves assigning predefined labels or classes to input data based on their features. In this project, the credit score brackets were treated as different classes, and the aim was to accurately classify individuals into these classes based on their bank details and credit-related information.

# Classification Algorithms
To solve the credit score classification problem, various classification algorithms were explored. The following algorithms were considered:

Logistic Regression: A linear model that predicts the probability of an instance belonging to a particular class based on its features.

k-Nearest Neighbors (k-NN): A non-parametric algorithm that classifies instances by identifying the k nearest neighbors in the feature space.

Naive Bayes: A probabilistic classifier that calculates the probability of each class given the input data, assuming independence between features.

Decision Trees: Tree-based models that make decisions by recursively partitioning the feature space based on the most informative features.

Random Forest: An ensemble method that combines multiple decision trees to improve classification performance.

Neural Networks: Deep learning models consisting of interconnected layers of artificial neurons that can learn complex patterns and relationships.

# EDA & Data Preprocessing
Exploratory Data Analysis (EDA) was performed to gain insights into the dataset and understand its characteristics. This involved visualizing the data, identifying patterns, and handling missing values or outliers.

Data preprocessing steps were applied to prepare the data for classification algorithms. Numerical data was checked for missing values and outliers, and appropriate actions such as imputation or removal were taken. Categorical data was encoded using techniques like one-hot encoding or label encoding. Multicollinearity, the presence of strong correlations between independent variables, was checked using methods like the Variance Inflation Factor (VIF).

# Modeling
After EDA and data preprocessing, the data was ready for modeling. The dataset was split into a training set and a separate test set for evaluating model performance. Each classification algorithm mentioned earlier was implemented and trained on the training set. The models' performance was assessed using evaluation metrics such as accuracy, precision, recall, and F1-score. The best-performing model was selected based on these metrics.

# Conclusion
In conclusion, this project successfully developed an intelligent system for credit score classification using supervised learning techniques. By applying various classification algorithms and performing thorough EDA and data preprocessing, the system achieved accurate predictions and reduced manual efforts in assessing creditworthiness. The chosen model can now be deployed and used to categorize individuals into credit score brackets, benefiting the finance company's decision-making process.
