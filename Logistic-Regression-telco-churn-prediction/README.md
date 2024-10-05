# Customer Churn Prediction 

This project aims to predict customer churn within a telecommunications company using historical customer data. Understanding and anticipating customer churn is crucial, as retaining existing customers is often more cost-effective than acquiring new ones. By identifying customers at risk of leaving, targeted retention strategies can be developed, ultimately enhancing customer satisfaction and company revenue.

## Project Overview 

The primary objective of this analysis is to predict which customers are likely to leave the service in the near future. The dataset utilized for this project includes a range of customer-related information that can provide valuable insights into customer behavior.

**The dataset includes information about:**

- **Churn**: Whether the customer left within the last month.
- **Services**: Details on services each customer has signed up for, including phone, internet, online security, device protection, tech support, and streaming options.
- **Account Information**: Contract type, payment method, billing information, tenure with the company, monthly charges, and total charges.
- **Demographics**: Gender, age range, and whether customers have dependents.

## Dataset Features 

The dataset contains various features essential for analyzing customer behavior, including:

- **Churn**: A binary indicator of whether the customer left the company.
- **Tenure**: Duration of the customer's relationship with the company.
- **Demographics**: Customer age, gender, and household composition.
- **Services**: Information about the services customers have subscribed to.
- **Financial Information**: Monthly and total charges.

## Model Overview 

We implemented a Logistic Regression model using Scikit-learn to analyze the dataset. Logistic Regression is well-suited for binary classification problems and allows us to assess the likelihood of churn based on various customer features. 

The model was trained on a portion of the dataset, allowing us to predict churn for a separate test set.

## Model Evaluation 

The performance of the Logistic Regression model was evaluated using several metrics:

- **Jaccard Index**: A measure of accuracy, indicating the overlap between predicted and actual churn values.
- **Confusion Matrix**: Provides insight into true positives, false positives, true negatives, and false negatives, offering a clear view of model performance.
- **Precision, Recall, and F1-Score**: Metrics that assess the model's ability to correctly identify churned customers.
- **Log Loss**: A metric that evaluates the accuracy of the predicted probabilities.

### Key Findings 

- The model achieved an average accuracy (F1-score) of approximately 0.72, indicating a reasonable balance between precision and recall in predicting churn.
- The confusion matrix revealed that while the model performed well in identifying non-churning customers (with a high true negative rate), there were notable false negatives, indicating some churned customers were misclassified as staying.
- The model's evaluation metrics suggest that further enhancements could be made, potentially through feature engineering or the inclusion of additional relevant data.

## Project Structure

- **Notebook**: Contains the code for loading the dataset, preprocessing, model training, and evaluation.
- **Data**: The dataset used for this project is accessible through the notebook.

## Google Colab

For those who prefer to run the project in the cloud, you can execute it on Google Colab. Simply click the link below to open the notebook and run it:

[Customer Churn Prediction using Logistic Regression on Google Colab](https://colab.research.google.com/drive/1rc7OgVDg_P6S4nIdAv7qGC7xuRSl5Sbk?usp=sharing)

## Conclusion 

The analysis of customer churn using the telecommunications dataset has highlighted several key aspects of customer behavior. By employing Logistic Regression, we have been able to identify critical factors influencing customer retention. Our findings underscore the importance of targeted retention strategies that can be developed based on the predictive insights gained from the model. 

By focusing on high-risk customers identified through this analysis, the telecommunications company can implement proactive measures to improve customer satisfaction and reduce churn rates. Continued refinement of the model and the inclusion of additional features could further enhance predictive accuracy, ultimately supporting the company's goals of customer retention and profitability.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page.

## Credits

This project was developed as part of the IBM Machine Learning course on Coursera.
