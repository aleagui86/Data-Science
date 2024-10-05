# Customer Churn Prediction 

This project focuses on predicting customer churn in the telecommunications sector, a crucial challenge for businesses aiming to enhance customer retention and reduce revenue loss. By identifying which customers are likely to leave the service, companies can implement proactive retention strategies, optimizing marketing spend and improving overall customer satisfaction.

## Project Overview 

In this analysis, we aim to predict customer churn using a variety of features that provide insights into customer behavior and preferences. Understanding the factors that influence churn enables organizations to tailor their retention efforts, thereby reducing attrition rates and maintaining a steady revenue stream. The key areas of focus in our project include:

- **Customer Churn**: This feature identifies customers who have terminated their service within the last month, providing critical insight into retention trends.
- **Customer Services**: Detailed information about the services each customer subscribes to, such as phone lines, internet services, streaming, and security offerings.
- **Account Information**: Essential details regarding contract type, payment methods, billing information, and the length of time the customer has been with the company.
- **Demographics**: Information on the customer’s gender, age, and whether they have dependents, which can influence service usage and satisfaction.

## Dataset Features 

The dataset contains several important features that allow for a comprehensive analysis of churn:

- **Churn**: A binary variable indicating whether the customer left within the last month.
- **Tenure**: The duration of time a customer has been with the company, which can be a key indicator of loyalty.
- **Services**: A categorical variable indicating the types of services used by the customer, such as phone, internet, and additional services.
- **Billing Information**: Features such as monthly charges and total charges that help identify pricing sensitivity.
- **Demographics**: Additional demographic variables, including gender and age, that can affect customer behavior and preferences.

## Model Overview 

For this analysis, we employed Logistic Regression from the Scikit-learn library, a widely used method for binary classification problems. Logistic Regression is particularly suited for this task due to its interpretability and ability to model the relationship between multiple independent variables and the probability of churn. By understanding these relationships, businesses can pinpoint at-risk customers and tailor their interventions accordingly.

## Model Evaluation 

To evaluate the effectiveness of our model, we used several key metrics:

- **Jaccard Index**: This metric evaluates the accuracy of the predictions made by the model, providing a clear picture of its performance.
- **Confusion Matrix**: A detailed breakdown of the model's predictions, highlighting true positives, true negatives, false positives, and false negatives.
- **Precision, Recall, and F1-Score**: These metrics assess the model's ability to balance precision (the accuracy of positive predictions) and recall (the ability to capture all actual positives), crucial for understanding its real-world applicability.
- **Log Loss**: This metric measures the performance of the model when predicting probabilities, providing insight into how well the model differentiates between classes.

## Project Structure

The project is organized as follows:

- **Notebook**: Contains the code for loading the dataset, performing data preprocessing, and building the predictive model.
- **Data**: The dataset used for this project is available in the repository, ensuring reproducibility and ease of access for further analysis.

## Conclusion

The analysis of customer churn has revealed several key insights that can significantly impact business strategy. 

1. **Service Usage**: Customers who utilize multiple services tend to show higher retention rates, highlighting the importance of bundled offerings in retaining clients.
2. **Tenure Impact**: Longer-tenured customers are less likely to churn, suggesting that building long-term relationships through personalized engagement can reduce attrition.
3. **Demographic Insights**: Certain demographic groups, particularly younger customers, show higher churn rates. Targeted retention strategies, such as loyalty programs or tailored communication, may be necessary to engage these segments effectively.
4. **Pricing Sensitivity**: Analysis indicated a correlation between high monthly charges and increased churn likelihood. Competitive pricing or value-added services may be essential to retain these customers.

By leveraging these insights, companies can refine their customer retention strategies and improve customer satisfaction, ultimately enhancing their bottom line.

## Google Colab

For those who prefer to run the project in the cloud, it is available on Google Colab. You can easily access and execute the notebook by clicking the link below:

[Telco Churn Prediction using Logistic Regression on Google Colab](https://colab.research.google.com/drive/1rc7OgVDg_P6S4nIdAv7qGC7xuRSl5Sbk?usp=sharing)

## Contributing

Contributions, issues, and feature requests are welcome. If you encounter any problems or have ideas for enhancements, feel free to check the issues page and contribute.

## Credits

This project was developed as part of the IBM Machine Learning course on Coursera, which provided the foundational knowledge and skills necessary to undertake this analysis.
