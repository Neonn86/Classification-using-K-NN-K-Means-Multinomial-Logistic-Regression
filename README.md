# Classification using K-NN, K-Means, Multinomial Logistic Regression
## Objective
The goal is to classify the wine quality into High, Medium, and Low, and compare the classification accuracy of these 3 models.

## Data Source
The data comes from the public source, documenting the properties of the wine, such as Acidity, Sugar, and PH etc.

## Structure
### EDA
Based on the distribution of the wine quality, seperate the dataset into Low, Medium, and High.
- The medium is large propotion in the dataset, which is nearly 80%.
### K-NN
Trialed on K= 1 / 3 / 5.
- The model achieved 97.5% accuracy with k is 3.
### Multinomial Logistic Regression
The accuracy of the multinomial logistic regression classifier on the train data is 100%, on the test data is 100%.
### K-Means
It's hard to tell which cluster correspond to which quality, but comparing to the confusion matrix of the multinomial logistic regression, it's accuracy is apparently lower. So in this scenario, the supervised algorithm wins.
## Conclusion
For this particular dataset, supervised algorithm outperform the unsupervised ones. Among supervised algorithm, Multinomial Logistic Regression is the best classifier.
