# Day 2

- ** It took a lot of time to get the model to predict correctly. I still have some doubts regarding the feature selection, which I will try to learn.**

## Feature selection

- I seperated numerical, nominal and ordial values and processed them seperately.
- I used one hot encoder for nominal values and manual mapping for ordinal values.
- I used power transformer on numerical values.

## Models

- I ran the MSE and R2 scores for Linear regression, Lasso, and Ridge. 
- Lasso is the best among the models, as there are more features and a lot of them do provide a lot of information, their coefficients are put to 0, so feature selection is also done automatically.
- Ridge is slightly better than Linear regression as it will decrease the value of the not so important features, but not entirely putting them as 0, as there are many features it doesnt give us the results on par with Lasso.