# Machine Leanering Practice

## Overview

Pratice importing, using, and analyzing data, as well as testing and implementing algorithims. The program follows an [instruction guide](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/) and gave me experience with Windows Powershell, machine learning algorithims, Pyplot, datasets, importing libraries, and Numpy.

## Features:

### Data Examination and Analysis

The dataset used is the ["Iris Flower Dataset"](https://en.wikipedia.org/wiki/Iris_flower_data_set). The dataset is first summarized in numerical context, then Pyplot is used to visualize said data. Before being used by the algorithims, the data is sectioned off to produce a validation dataset. This allows me to evaluate the results of the algorthim through comparison.

### Algorithim Testing and Results

Six algorithims are put in competition to discover the most accurate for this dataset. The ones tested are [Logistic Regression (LR)](https://en.wikipedia.org/wiki/Logistic_regression), [Linear Discriminant Analysis (LDA)](https://en.wikipedia.org/wiki/Linear_discriminant_analysis), [K-Nearest Neighbors (KNN)](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm), [Classification and Regression Trees (CART)](https://www.digitalvidya.com/blog/classification-and-regression-trees/#:~:text=A%20Classification%20and%20Regression%20Tree,prediction%20for%20the%20target%20variable.), [Gaussian Naive Bayes (NB)](https://iq.opengenus.org/gaussian-naive-bayes/#:~:text=Gaussian%20Naive%20Bayes%20is%20a,distribution%20and%20supports%20continuous%20data.&text=Naive%20Bayes%20are%20a%20group,technique%2C%20but%20has%20high%20functionality.), and [Support Vector Machines (SVM)](https://en.wikipedia.org/wiki/Support-vector_machine). The accuracy data for these algorithims were also compared numerically, then graphed. The Support Vector Machine was found to be the most accurate for this project, with an accuracy rate of about 98%.

The Support Vector Machine algorithim was then used to make predictions about the dataset and evaluated for accuracy. The evaluation was done using a percentage of accuracy, a confusion matrix, and a classification report:

0.9666666666666667
[[11  0  0]
 [ 0 12  1]
 [ 0  0  6]]
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        11
Iris-versicolor       1.00      0.92      0.96        13
 Iris-virginica       0.86      1.00      0.92         6

       accuracy                           0.97        30
      macro avg       0.95      0.97      0.96        30
   weighted avg       0.97      0.97      0.97        30




