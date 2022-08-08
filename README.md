# Random Forest knowledge

- Supervised Machine Learning Algorithm
- used widely in Classification and Regression problems
- builds decision trees on different samples
    - takes their majority vote for classification
    - take average in case of 
    regression

- most important features : it can handle the data set containing
    -   continuous variables as in the case of regression
    -  categorical variables as in the case of classification

- Ensemble:  means combining multiple models.it uses two types of methods:  
  - Bagging (Bootstrap Aggregation):  creates a different training subset from sample training data with replacement & the final output is based on majority voting. For example,  Random Forest.
  - Boosting:  combines weak learners into strong learners by creating sequential models such that the final model has the highest accuracy. For example,  ADA BOOST, XG BOOST

- Important Features of Random Forest
    - Diversity:  Not all attributes/variables/features are considered while making an individual tree, each tree is different.
    - Immune to the curse of dimensionality:  Since each tree does not consider all the features, the feature space is reduced.
    - Parallelization: Each tree is created independently out of different data and attributes. This means that we can make full use of the CPU to build random forests.
    - Train-Test split: we don’t have to segregate the data for train and test as there will always be 30% of the data which is not seen by the decision tree.
    - Stability: Stability arises because the result is based on majority voting/ averaging.


 
