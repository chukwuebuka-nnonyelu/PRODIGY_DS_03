# Decision Tree Classifier for Term Deposit Subscription Prediction

## Overview
This project develops a predictive model to classify whether a customer will subscribe to a term deposit using a Decision Tree Classifier. The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing).

## Key Highlights

- **Data Processing:**
  - Explored the dataset and identified both categorical and numerical features.
  - Handled outliers using the Interquartile Range (IQR) method.
  - Encoded categorical variables with Label Encoding.

- **Model Building:**
  - Split the dataset into training (80%) and testing (20%).
  - Selected a Decision Tree Classifier and performed hyperparameter tuning using GridSearchCV.

- **Results:**
  - Achieved an accuracy of **98.4%** on the test set.
  - Notable performance metrics:
    - Class 0 (Not Subscribed): Precision **98.42%**, Recall **99.98%**
    - Class 1 (Subscribed): Precision **93.33%**, Recall **16.09%**

- **Conclusion:**
  - The model effectively predicts non-subscribers but struggles with identifying subscribers due to class imbalance. Recommendations for exploring alternative algorithms are provided.
