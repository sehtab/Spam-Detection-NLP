# Spam-Detection-NLP

https://colab.research.google.com/drive/1akCxgzCmGDs3ODJbO1oFeJTvVCe4fCb0?usp=sharing 

# Objective:

The objective of this ICP is to classify spam emails and for that the related dataset is uploaded and analyzed.

# Approaches

At first, necessary libraries are imported. The dataset is uploaded then tokenized and splitted. After split, trainset data is synthethized with word vector,
and PCA analysis is done. Then word level tf-idf, count word tf-idf is done over train dataset. 
Then train datset is analyzed with different classifier:  MultinomialNaive Bayes Theorem, Logistic Regression, KNN, Random Forest, Decision Tree and  
SVC with GridSearchCV to get best hyperparameters.

All classifiers accuracy, precision, recall and F1 score is evaluated.

# Datasets

For this ICP from spam.csv is used as dataset.

# Results:

Results are generated from sklearn library and they are working good. I am getting maximum accuracy from SVC with rbf kernel classifier which is of 99% for word level tf-idf

# Challenges

For this icp, accuracy plot get conjungted for too many data.

# Planned Work

spam.csv attached with the colab file.Then several tf-idf for classification and featureset is being created. After splitting the dataset in train and test 
with 20% in test set classifiers are implemented and classifiers are performance are evaluated through Accuracy, Recall, Precision and F1 -score.

![image](https://user-images.githubusercontent.com/70243598/192072736-8d12d11a-c38c-420f-a1f5-02f01eb8e103.png)
