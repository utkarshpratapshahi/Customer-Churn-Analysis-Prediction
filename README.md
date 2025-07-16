# Customer-Churn-Analysis-Prediction

Customer churn occurs when a customer stops using a company’s service lead to revenue loss. Analyzing churn helps businesses understand why customers leave and how to improve retention. High churn rates can affect revenue and business growth. By analyzing churn patterns businesses can take proactive steps to retain customers.

# Dataset
I have used Telco Customer Churn dataset to predict churn.

# Analyzing Churn Distribution
We check the number of churners and non-churners to understand the balance of the dataset. This is represented in the below image:
<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/ca47b3b6-6023-4583-a364-c9e829289194" />

# Data Preprocessing
We began by performing essential data preprocessing steps, including handling missing and incorrect values to ensure data quality. Categorical variables were encoded appropriately to make them usable by machine learning algorithms.

Following this, we conducted feature selection to retain the most relevant variables and then split the dataset into training and testing sets to evaluate model performance effectively.

# Feature Scaling
Since the dataset contained features with varying scales, we applied standardization using StandardScaler. This step helps prevent the model from being biased toward features with larger numerical ranges and improves the convergence speed of optimization algorithms such as gradient descent.

# Model Training
For model training, we used the Random Forest Classifier, an ensemble learning method that aggregates the results of multiple decision trees to make more accurate and robust predictions. Random Forest helps reduce overfitting and increases generalization performance.
We evaluate precision, recall and accuracy using a confusion matrix. 
<img width="563" height="455" alt="image" src="https://github.com/user-attachments/assets/7a8e3086-e0a5-4080-9299-72608706e4ba" />




