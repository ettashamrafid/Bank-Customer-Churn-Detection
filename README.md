# Bank-Customer-Churn-Detection
Predict customer churn in a banking business using machine learning. Explore various algorithms like Random Forest, Gradient Boosting, and LightGBM. Evaluate models based on accuracy and F1 score. Repository includes dataset, preprocessing scripts, and Jupyter Notebook for comprehensive analysis.

---

# Bank Customer Churn Prediction

## Dataset Description:
The dataset contains the following parameters:
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary

Based on these parameters, a machine learning model was developed to predict whether a customer exited the bank or not.

## Data Preprocessing:
The dataset underwent thorough cleaning and preprocessing to ensure its suitability for the project. Data preprocessing involved handling missing values, outlier detection, and feature scaling. Categorical variables like Geography and Gender were encoded appropriately for model compatibility.

## Machine Learning Models:
Several machine learning algorithms were explored for this project, including:
- Linear Regression
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM
- Artificial Neural Network (with and without dropout regularization)

## Evaluation Metrics:
The model performance was evaluated using the following metrics:
- Accuracy
- F1 Score

## Results:
The best results were achieved using the LightGBM model, with a training accuracy and F1 score of 1.0. The testing accuracy was also 1.0, with an F1 score of 0.6, which was the second-best in terms of F1 score. The artificial neural network without dropout regularization performed exceptionally well, with a slight margin of 0.03 over other models. Random Forest and Gradient Boosting models also showed competitive performance.

## How to Use:
1. Clone this repository to your local machine.
2. Ensure you have Python and necessary libraries (pandas, scikit-learn, lightgbm, xgboost) installed.
3. Run the Jupyter Notebook or Python scripts to train and evaluate the models.
4. Explore the code to understand the preprocessing steps, model training, and evaluation process.

Feel free to experiment with different models or modify the preprocessing techniques to enhance the model's performance further.

## Acknowledgments:
- The dataset used in this project was sourced from [https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling].
- Special thanks to the open-source community for their invaluable contributions to data science libraries and tools.

For any questions or inquiries, please contact [ettashamrafid@gmail.com].

---

This README provides a clear overview of your project, the dataset, preprocessing steps, models used, evaluation metrics, results, and instructions on how to use the project. Make sure to replace placeholders like `[source name/link]` and `[your email address]` with the appropriate information before sharing your project publicly.
