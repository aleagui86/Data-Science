# Customer Churn Prediction 

This project focuses on predicting customer churn using a telecommunications dataset. The goal is to identify which customers are likely to leave the service and to develop targeted customer retention strategies. The dataset is based on historical customer data, and we use Logistic Regression to model churn.

## Project Overview 

In this project, we aim to predict customer churn based on the following information:

- **Customer Churn**: Identifies customers who have left the company within the last month.
- **Customer Services**: Details on services each customer has signed up for, such as phone lines, internet services, streaming, and security services.
- **Account Information**: Contract type, payment method, billing info, and tenure with the company.
- **Demographics**: Gender, age, and whether they have dependents.

## Dataset Features 

- **Churn**: Whether the customer left within the last month.
- **Tenure**: How long the customer has been with the company.
- **Services**: Including phone, internet, and additional services.
- **Billing Information**: Monthly charges and total charges.
- **Demographics**: Gender, age, and more.

## Model Overview 

We implemented Logistic Regression from Scikit-learn for this analysis. Logistic Regression was chosen due to its ability to handle binary classification problems and its suitability for understanding the relationship between multiple independent variables and the likelihood of churn.

## Model Evaluation 

The model is evaluated using various metrics such as:

    Jaccard Index: Evaluates the accuracy of predictions.
    Confusion Matrix: To analyze the true positives, true negatives, false positives, and false negatives.
    Precision, Recall, and F1-Score: To assess the model's ability to balance precision and recall.
    Log Loss: Measures performance when predicting probabilities.

## Project Structure

    Notebook: Contains the code for loading the dataset, data preprocessing, and modeling.
    Data: The dataset used for this project is available in the repository.
    
## Google Colab

If you prefer to run the project in the cloud, you can execute it on Google Colab. Simply click the link below to open the notebook and run it:
[Telco Churn Prediction using Logistic Regression on Google Colab]([https://colab.research.google.com/drive/1t4vF09UVlPeLbSPV8fn99IJ0fcMpUVJ8?usp=sharing](https://colab.research.google.com/drive/1rc7OgVDg_P6S4nIdAv7qGC7xuRSl5Sbk?usp=sharing))

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page.

## Credits

This project was developed as part of the IBM Machine Learning course on Coursera.
