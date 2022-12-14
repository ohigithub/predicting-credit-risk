# Predicting Credit Risk

## Objective
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API. I used their 2019 data to create machine learning models to classify the risk level of given loans for 2020.

## Predictions & Result Comparisons

Before running the model, I believed the linear regression model would perform better on the scaled data as there would not be an issue of outliers to throw it off. I beleived the random forest model would perform better on the unscaled data because it would be better at handling the wide range of values within the data set. Comparing the two models, the training score was 30% more accurate than the test score.
