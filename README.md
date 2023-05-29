# LGMVIP--DataScience-Task-Numer-1

## Table of Content

1. Introduction
2. Classification Models

   K Nearest Neighbours

   Decision Tree
 
   Support Vector Machine
 
   Logistic Regression
   
   Random Forest
 
7. Results
8. Conclusion

## INTRODUCTION

Iris is a genus of around 300 species of flowering plants. It takes the name from the Greek goddess of rainbow, Iris. The Iris flower data set is also know as the Fisher's Iris data set. It is a multivariate data set introduced by Ronald Fisher in his paper, The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

The data set is available at https://archive.ics.uci.edu/ml/datasets/iris, the errors are modified as well. It consists the following information for 150 samples,

sepal length (in cm)
sepal width (in cm)
petal length (in cm)
petal width (in cm)
class:
Iris Setosa
Iris Versicolour
Iris Virginica

## CLASSIFICATION MODELS

Classification models can be used to predict the dependent variable (class of each flower). Here we are going to use 5 different algorithms for classification namely, K-Nearest Neighbours, Decision Tree, Support Vector Machine, Random Forest and Linear Regression. Atlast we compare their accuracy to find the suitable classification technique for this problem. The given dataset is seperated into two seperate train and test sets. The train set is used to train the model, and the test set is used to predict the accuracy of each model. Finally, we compare the results. Here, 70% of the dataset was considered for training and 30% of the dataset for testing.

### Accuracy of Each Model using test data

|     Algorithm           | Accuracy  |
|------------------------:|-----------|
|   K Nearest Neighbour   |     91    |
|   Decision Tree         |     93    |
|   Random Forest         |     91    |
|   Support Vector Machine|     91    |
|   Logistic Regression   |     83    |

