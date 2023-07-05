# service-score-prediction
Task: Investigate how we can train a model using the 75 services and their scores, to forecast / predict the remaining 200+ services we have data from via the digital dashboard

Machine Learning Model:
A classification random forest model was used to predict the score. The random forest model was used because:
1. of the ability to handle datasets with high dimensionally. The model also outputs the importance of each feature which is a handy feature.
2.  It has an effective method for estimating missing data and maintains accuracy when large proportion of the data are missing.
3. It has methods for balancing errors in data sets where classes are imbalanced.
4. Better accuracy than other classification algorithms

Training and Test Split:
With the score, the dataset has a size of 69. As we have a small dataset, I split the data into 60% training (38 rows), and 40% testing (26 rows). A seed was set to ensure that results are reproducible.
