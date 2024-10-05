# Telco Classifier Using K-Nearest Neighbors

## Brief Overview

A telecommunications provider has segmented its customer base by service usage patterns, categorizing customers into four groups. If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers. This is a classification problem; given the dataset with predefined labels, we need to build a model to predict the class of a new or unknown case.

The example focuses on using demographic data, such as region, age, and marital status, to predict usage patterns.

The target field, called `custcat`, has four possible values corresponding to the four customer groups:

1. Basic Service
2. E-Service
3. Plus Service
4. Total Service

Our objective is to build a classifier to predict the class of unknown cases using a specific type of classification called K-Nearest Neighbors (KNN).

## Methodology

### Data Visualization and Analysis

The first step involved analyzing the distribution of each class in our dataset and visualizing demographic features, such as income, using histograms.

### Feature Set

We defined our feature set `X`, which includes the following demographic attributes:
- Region
- Tenure
- Age
- Marital Status
- Address
- Income
- Education Level
- Employment Status
- Retirement Status
- Gender
- Residential Status

The target variable `y` is the customer category.

### Data Normalization

To improve model performance, we standardized the data using `StandardScaler`, ensuring it has a zero mean and unit variance, which is crucial for distance-based algorithms like KNN.

### Train-Test Split

We split the dataset into training and testing sets (80/20) to evaluate the model's out-of-sample accuracy effectively.

### Classification Using K-Nearest Neighbors (KNN)

We implemented the KNN algorithm, initially setting `k=4`. The model was trained on the training set, and predictions were made on the testing set. We evaluated the model's accuracy by comparing the predicted and actual classes.

### Hyperparameter Tuning

We explored different values of `k` (from 1 to 10) to determine the optimal number of neighbors, calculating the accuracy for each value. The best accuracy was found with `k=9`.

## Conclusions Based on Findings

The KNN classifier successfully predicted customer categories based on demographic data with a notable accuracy rate. By adjusting the value of `k`, we identified that `k=9` yielded the highest accuracy for our model.

The primary distinction between K-Nearest Neighbors and K-Means is their purpose and application:
- **K-Nearest Neighbors (KNN)** is a **supervised learning algorithm** used for classification and regression tasks, where the algorithm predicts the label of a new data point based on the majority class among its `k` nearest neighbors in the feature space.
- **K-Means**, on the other hand, is an **unsupervised learning algorithm** used for clustering, where the algorithm partitions data into `k` distinct clusters based on similarity, without prior labeled data.

In summary, KNN is suitable for predictive modeling with labeled data, while K-Means is best for discovering inherent groupings in unlabeled datasets.

## Google Colab

For those who prefer to run the project in the cloud, you can execute it on Google Colab. Simply click the link below to open the notebook and run it:

[Telco classifier using K-Nearest Neighbors](https://colab.research.google.com/drive/1UX8Nurb-bAHR7m0H4VR2M-cFhFqB-D5k?usp=sharing)

## Future Work

Future work could involve testing additional machine learning algorithms, exploring feature engineering techniques, or employing ensemble methods to further improve predictive accuracy.
