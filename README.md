# CS506_hw5

bstanfor@bu.edu
Kaggle username: bstanfor

My predictive model is a multinomial logistic regression. Using a bag of words in addition to n-grams where n ranges from 1 to 3, inclusive. I chose a multinomial logistic regression as this is a classification problem with more than 2 possible outcomes. Bag of words was used in order to identify words and n-grams highly correlated with scores. The use of n-grams allows the predictive model to differentiate phrases like "very good" from "not good". In the vectorization of this, I limited the model to 20,000 features due to memory constraints. 
