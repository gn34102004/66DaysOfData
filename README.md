# 66DaysOfData

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



