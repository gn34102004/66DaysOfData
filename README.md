Hi Everyone,

Day 10 of #66DaysOfData challenge

Today I have learnt about P Value and Hypothesis Testing.

1) P Value - It is a probability for the "Null Hypothesis" to be true.

It is also known as Significance Value and denoted by α(alpha).

-> Null Hypothesis - It treats everything same or equal.

-> Alternate Hypothesis - There is a difference.

2) Hypothesis Testing - Depending on P value the Hypothesis Testing is done in several dataset. If P<=0.05 the Null Hypothesis is rejected and Alternate Hypothesis becomes True for the datasets.

-> One Sample Proportion Test - If only One Categorical Feature is there.

-> Chi Square Test - Two Categorical Feature is there.

-> T Test - One Continous Variable along with Categorical Feature.

-> Correlation - Two Continous Variable are present.

-> Anova Test - If there is Continous Variable and a Categorical Variable present in which, the Categorical Variable must have more than Two Features.





Hi Everyone,

Day 9 of #66DayOfData challenge 

Today I have studied the concept of 

1) R^2 and Adjusted R^2

-> R^2 : It is used to check the goodness of the best fit line. The value of R^2 increases with the increase of independent feature. If the value is <0 then it is worser than the average best fit line.

-> Adjusted R^2 : It penalizes attribute that are not correlated which makes the value to Decrease. If the attribute is correlated the value of adjusted R^2 increases(0 to 1), which is good for best fit line.

2) Bias and variance

-> Bias : Error of the training data.

-> Variance : Error of the testing data.

High Bias, High Variance = Underfitting

Low Bias, High Variance = Overfitting

Low Bias, Low Variance = Generalized Model




# 66DaysOfData

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



