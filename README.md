# To download the BERT model used in this repo

## URL: https://www.kaggle.com/qinhanmin/bert-base-uncased

## Technologies Used:

-   BERT Model
-   PyTorch
-   Transformers
-   Scikit Learn
-   Pandas

## Summary

The following kernel uses BERT to classify IMDB Movie Reviews from the IMDB 50k Dataset. The model gives 93% Accuracy. The Model predicts whether the sentiment of the sentence given as parameters is negative sentiment or a positive sentiment. It gives a percentage out of 100% of how likely the sentence is to be positive or negative.

The Jupter Kernel (ipynb) file provides the steps from preprocessing the data to setting up BERT and lastly, making a model on PyTorch

## Running on LocalHost

The API is deployed and served on Flask on Localhost 5000 to predict the sentiment of the sentence given as parameters.
