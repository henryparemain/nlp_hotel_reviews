# nlp_hotel_reviews
Combining NLP methods with Logistic Regression, KNN and Decision Trees to predict the sentiment of hotel reviews. 

Part 1 explores the dataset, carrying out EDA to see which features could be useful. The text of the reviews is vectorized, creating two sparse matrices (one for positive reviews, the other for negative reviews). These matrices are ultimately combined with the original numerical dataset, into a single dataframe that is to be used in Part 2.

Part 2 looks at various supervised learning approaches. Multiple rabbit holes are explored in terms of model performance, and Cross Validation is used to optimise the parameters of the logistic regression model. Feature engineering is carried out, successfully improving the performance of the baseline model. 