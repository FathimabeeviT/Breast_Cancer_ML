Overview
This project uses supervised learning techniques to classify breast cancer patients into  benign categories based on various features. The dataset used is the Breast Cancer Dataset from sklearn.( 569 samples,30 features,2classes)
This project start with load data. secondly data preprocessing(this data set no missing values. However,data preprocessing is  mandatory.if have may null values inthis set,  it will  be chance to effect the prediction)
1. Logistic Regression-(it works by modeling the relationship between a set of independent variables (features) and a binary dependent variable (outcome) using a logistic function. The algorithm estimates the probability that a given input belongs to a particular class.This dataset is designed to predict a binary outcome (e.g., yes/no, 0/1), logistic regression is a natural choice.
2. Decision Tree Classifier-( it works by splitting the dataset into subsets based on the value of input features  it's worth noting that decision trees can be prone to overfitting, especially if they grow too deep. This can be mitigated by pruning the tree, setting a maximum depth, or using ensemble methods like Random Forests.
3. Random Forest Classifier-(It is an ensemble learning method that combines multiple decision trees to create a more robust and accurate model. It operates by building many decision trees during training and outputting the class that is the mode of the classes (for classification) of the individual trees.If this dataset has complex relationships, possible noise, or you require a model that is both accurate and interpretable in terms of feature importance, a Random Forest Classifier could be a highly suitable choice.
4. Support Vector Machine (SVM)-( SVM is a supervised machine learning algorithm that classifies data by finding an optimal line or hyperplane that maximizes the distance between each class in an N-dimensional space.This algorithm works by finding the hyperplane that best separates the data points of different classes. In a two-dimensional space, this hyperplane is simply a line, but in higher dimensions, it becomes a hyperplane.
SVM is a strong choice if our dataset involves high-dimensional data, non-linear relationships, or you need a model with good generalization capabilities.)
5. k-Nearest Neighbors (k-NN)-(This algorithm used for classification (and sometimes regression) tasks. It is based on the principle that similar data points are close to each other in feature space.k-NN is a good choice if we have a dataset where the relationship between features and classes is well-defined in terms of proximity in the feature space, and you prefer a model that is easy to understand and implement.


conclusion:
. Logistic Regression achieved the highest accuracy score of 97.2%.
. Decision Tree Classifier performed the worst with an accuracy score of 93.7%. this data set perfectly suitable for Logistic Regression.
   
