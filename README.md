Aim- The main aim was to compare different techniques that can be used in fraud detection and find one of the best techniques among them.

Dataset- The dataset for this project is taken from Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud). This dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.

Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.

Detection Techniques Used-
1. Decision Tree- A decision tree is a tree-like graph with nodes representing the place where we pick an attribute and ask a question; edges represent the answers to the question; and the leaves represent the actual output or class label. They are used in non-linear decision making with simple linear decision surface.
2. Random Forest- Random forest classifier creates a set of decision tree from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object.
3. Logistic Regression- Logistic regression is a classification algorithm used to assign observations to a discrete set of classes. Unlike linear regression which outputs continuous number values, logistic regression transforms its output using the logistic sigmoid function to return a probability value which can then be mapped to two or more discrete classes.
4. Neural Networks- Neural networks are parallel computing devices, which are basically an attempt to make a computer model of the brain. The main objective is to develop a system to perform various computational tasks faster than the traditional systems. This tutorial covers the basic concept and terminologies involved in Artificial Neural Network. Sections of this tutorial also explain the architecture as well as the training algorithm of various networks used in ANN.

Our Approach-
Firstly, we check if there is any relation between all the input variables, but the data was highly unbalanced, so we didn’t get any relation.
Afterwards we split our dataset into 70% train and 30% test using train_test_split.
Then we started building models for comparison. The first model we built was a decision tree which gives the accuracy of about 75%, the second model was random forest which gave the accuracy of 81%, the third model was logistic regression which gave the accuracy of 84% and the last model was neural networks which gave the accuracy of 99%.

Conclusion- Based on the results we can say that the neural networks are the most powerful model among all the other models we applied.
