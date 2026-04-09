# Leaf-Classification-
Classification problem, Supervised Machine learning.

OBJECTIVE:
The goal is to propose a method for leaf identification based on the provided leaf attributes
from the given dataset. In this project, supervised machine learning techniques such as logistic 
regression, SVM and random forest classifiers are selected and implemented. They are further 
attempted to improvise their performance by various methods.

DATASET INFORMATION:
The dataset consists of 16 attributes with 340 rows and 16 columns. The columns include class, 
specimen number, eccentricity, aspect ratio, elongation, solidity, stochastic convexity, isoperimetric 
factor, maximal indentation depth, lobedness, average intensity, entropy, average contrast, smoothness, 
third moment, uniformity. Class is selected as the target variable. There are 36 unique classes within 
the class column, while there are 16 unique specimens within the specimen number column.

CONCLUSION:
Random forest classifier and Logistic regression with class weights balanced performed well 
comparatively. The main problem associated with imbalanced dataset is that it can cause bias 
in the model performance. Thus, it can predict the majority class accurately and may not have 
enough examples to learn the pattern in the minority class. For this reason, using accuracy 
metrics can be misleading. Hence, all other metrics compared in results are more appropriate
