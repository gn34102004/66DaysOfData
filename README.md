# 66DaysOfData

Hi Everyone

Day 23 of #66DaysOfData challenge

Today I had learnt about Gradient boosting

It is a supervised machine learning technique that combines weak learners into a single strong learner. In which the algorithm gradually increases its accuracy.

The way that the Gradient boosting works are

Step 1: Compute the Base model which gives the output.

Step 2: Compute the Pseudo Residual.

Step 3: Fit a base learner to the pseudo-residuals.

Step 4: Construct the Decision Tree Sequentially

Step 5: Update the model.




Hi Everyone

As I was busy with my college work. I am back to the challenge.

Day 22 of #66DaysOfData challenge

Today I had learnt about AdaBoost (Adaptive Boosting)

It is a supervised machine learning boosting technique that combines multiple weak learners into a strong learner. Here the Base Learners are taken as Decision Tree of Stomps(which has only one depth).

Step 1: To find the Sample Weight of the given records.

Step 2: To find the Total Error of the selected stomp.

Step 3: To find the Performance of the Stomp, using the formula.

Now the wrong classified records will increase it's weight and the correct classiefied records will decrease it's weight.

Step 4: To Update the Weight, and create a Normalized weight column. Based on the normailzed values we will divide into buckets and the algorithm will sun upto a specified iteration, again new Stomp will be created from the wrong records based on the least entropy value.



Hi Everyone 

Day 21 of #66DaysOfData challenge

Today I had learnt about Random Forest

It is a supervised learning algorithm that uses bagging to train the decision trees. Bagging, also known as Bootstrap Aggregation, involves organizing original data into samples called Bootstrap Samples. 

Random forests are used for classification, regression. For classification through majority vote it gives output, and for regression output is calculated through mean, median.

Due to the multiple Decision Tree the model from Low Bias and High Variance gets converted to Low Variance which decreases the Error rate, and increases the Accuracy.





Hi Everyone 

Day 20 of #66DaysOfData challenge

Today I had learnt and implemented on Performance Metrics for Classification.

They are basically classified into

-> Confusion Matrix - It is a summarized table used to assess the performance of a classification model.

-> FPR(Type 1 Error) - It is the probability of falsely rejecting the null hypothesis.

-> FNR(Type 2 Error) - It's the ratio of false negatives to the total number of positives.

-> Recall(TPR, Sensitivity) - It is calculated by dividing the number of true positives by the number of positive instances.

-> Precision(+ve pred value) - It measures the accuracy of positive predictions

-> Accuracy - It measures the performance of a classifier.

-> F Beta - It's the weighted harmonic mean of precision and recall, with a value between 0 and 1.

-> ROC Curve/ Auc Score - It measures the performance of a classifier model. The area under the ROC curve (AUC) is a measure of the model's overall performance.

-> PR Curve - It's a graph that shows the relationship between precision and recall for different thresholds.


Hi Everyone 

Day 19 of #66DaysOfData challenge

Today I had learnt about Decision Tree

-> Decision Tree - It is a Supervised ML, and it uses a tree-like model.

-> Entropy - It helps us to measure the purity of the split(subset). It ranges from 0 to 1, in which 1 is the worst case whereas 0 is the best case.

-> Information Gain - It computes the average of all the entropy based on specific split.

-> Gini Impurity - It is computationally efficient as it takes shorter period of time for execution. It ranges from 0 to 0.5, if entropy is 0 to 1.



Hi Everyone

Day 18 of #66DaysOfData challenge

Today I have learnt and implemented on Cross Validation and its types.

-> Cross Validation- It is used to evaluate the performance of a model and prevents overfitting. 

Its types are:

-> Leave One Out CV(LOOCV) - Here only One sample  is selected as test data, the remaining will be selected as training data.

-> K Fold CV - Here it divides the given dataset into K equal parts, and taking Test data as one of the K part, and the rest K-1 will be the Training Data.

-> Stratified CV - It is similar to K Fold, but here it will make sure that Number of instances of each class for each experiment in the train-test dataset is taken properly

-> Time Series CV - It splits the data into multiple training and testing sets based on a specific time point.



Hi Everyone

Day 17 of #66DaysOfData challenge

Today I have learnt about "Logestic Regression" from Supervised Machine Learning Algorithm.

-> Logestic Regression- It accomplishes Binary Classification and Multiclass Classification tasks by predicting the probability of an outcome, event, or observation.

It is usually applied to a problem statement where these two classification problem is Linearly Separable.

The Cost Function/Optimizer must be Maximum to be classified correctly.

By the use of Sigmoid Function, it removes the affect og the outlier.

Hi Everyone

Day 11 of #66DaysofData challenge

Today I have studied the concept of

-> Variance - is a measure of how data points vary from the mean,

-> Standard Deviation - It is the square root of the variance.

-> Covariance - It measures the total variation of two random variables from their expected values. The drawback is it can only measure the directional relationship between two variables, and can't measure the strength.

-> Pearson Correlation Coefficient - It is the most common way of measuring a linear correlation. It can measure strength along with the direction of relationship. The valur ranges from [-1,1].

-> Spearman's Rank Correlation Coefficient - It is the same as Pearson, but as it calculate with the outliers certain condition must be followed.

We are supposed to sort out the two column in ascending order.

Next we need to add two more column by ranking them.

In next column comes the difference in the rank of the two column created.

The last column is the square of the difference of the rank, which is the di^2.

Hi Everyone,

Day 10 of #66DaysOfData challenge

Today I have learnt about P Value and Hypothesis Testing.

P Value - It is a probability for the "Null Hypothesis" to be true.
It is also known as Significance Value and denoted by α(alpha).

-> Null Hypothesis - It treats everything same or equal.

-> Alternate Hypothesis - There is a difference.

Hypothesis Testing - Depending on P value the Hypothesis Testing is done in several dataset. If P<=0.05 the Null Hypothesis is rejected and Alternate Hypothesis becomes True for the datasets.
-> One Sample Proportion Test - If only One Categorical Feature is there.

-> Chi Square Test - Two Categorical Feature is there.

-> T Test - One Continous Variable along with Categorical Feature.

-> Correlation - Two Continous Variable are present.

-> Anova Test - If there is Continous Variable and a Categorical Variable present in which, the Categorical Variable must have more than Two Features.

Hi Everyone,

Day 9 of #66DayOfData challenge

Today I have studied the concept of

R^2 and Adjusted R^2
-> R^2 : It is used to check the goodness of the best fit line. The value of R^2 increases with the increase of independent feature. If the value is <0 then it is worser than the average best fit line.

-> Adjusted R^2 : It penalizes attribute that are not correlated which makes the value to Decrease. If the attribute is correlated the value of adjusted R^2 increases(0 to 1), which is good for best fit line.

Bias and variance
-> Bias : Error of the training data.

-> Variance : Error of the testing data.

High Bias, High Variance = Underfitting

Low Bias, High Variance = Overfitting

Low Bias, Low Variance = Generalized Model



Hi Everyone,

Day 7 of my #66DaysOfData challenge 

Today I have learnt about Linear Regression.

It is one of the algorithm which comes under Supervised Learning. It provides relationship between an independent variable and a dependent variable to predict the outcome of future events.

Best Fit line- The line that tries to minimize the error(distance) between y^(the points which you find on best fit line) and y(actual points). 

The formula is y = mx + c


Convergence Theorem- The α(alpha) value must be vey small otherwise it wouldn't reach the Global minimum and keep bouncing.


Day 5:

Hi Everyone,

Day 5 of my #66DaysofData challenge

Today I started studying about different types of Feature Engineering encoding techniques.

There are two types: 

1) Nominal Encoding

-> One hot encoding- It is used to convert categorical to numeric feature. For instance, if there are 3 columns one of the column would be used for Dummy variable trap.

Dummy variable trap- They can be predicted from other variables

-> One hot Encoding with many categorical variables- If the dimension increases it would be difficult to use one hot encoding. If 100 categories are present the top 10 repeating categories will be selected and one hot encoding will be performed only for those 10 categories.

-> Mean Encoding- It is used to replace each category with mean of the target variable for that category.



2) Ordinal Encoding (Used when order of the categories are important)

-> Label Encoding- Converts categorical variable into numerical format and based on that ranks are predicted.

-> Target guided- Similar to mean encoding, the mean of the categories are calculated and ordered by ranks.



