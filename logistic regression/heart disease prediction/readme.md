# Introduction

In this repository we implement various Machine Learning (ML) techniques applied on the *__cancer dataset__* (__./dataset/heart_disease.csv__)
to predict wether given a patient with particular symptoms is likely to be affected by cancer or not.

---
### *Dataset*
The provided dataset contains the following features:

|      |   age |   sex |   cp |   trestbps |   chol |   fbs |   restecg |   thalach |   exang |   oldpeak |   slope |   ca |   thal |   target |
|-----:|------:|------:|-----:|-----------:|-------:|------:|----------:|----------:|--------:|----------:|--------:|-----:|-------:|---------:|
|    0 |    52 |     1 |    0 |        125 |    212 |     0 |         1 |       168 |       0 |       1   |       2 |    2 |      3 |        0 |
|    1 |    53 |     1 |    0 |        140 |    203 |     1 |         0 |       155 |       1 |       3.1 |       0 |    0 |      3 |        0 |
|    2 |    70 |     1 |    0 |        145 |    174 |     0 |         1 |       125 |       1 |       2.6 |       0 |    0 |      3 |        0 |
...
| 1023 |    50 |     0 |    0 |        110 |    254 |     0 |         0 |       159 |       0 |       0   |       2 |    0 |      2 |        1 |
| 1024 |    54 |     1 |    0 |        120 |    188 |     0 |         1 |       113 |       0 |       1.4 |       1 |    1 |      3 |        0 |


The methods implemented are listed as follows:
```
1. Linear Regression
2. K Nearest Neighbors
```
# TODO - List
- [x] Support Vector Classifier
- [x] Decision Tree Classifier
- [x] Random Forest Classifier