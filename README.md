# AirBnB Property Price Prediction
Project Motivation / Definition:

This project touches on four different topics that are important to enabling robust predictive models from the AirBnB dataset - these topics include:

1.  Data Exploration and Data Pre-processing using CRISP-DM as a framework
2.  Describe the process used to transform datasets to a form useful for predictive modeling and review the use of data visualization used to gain business understanding and to elucidate correlations
3.  Review constructing a neural net to perform AirBnB price predictions
3.  Explore Whether or not using language embeddings from a pre-trained model in-place of categorical variables enables price prediction at least as well as using randomly initialized feature embeddings

Libraries used during this analysis include:
torch, fastai, numpy, matplotlib, collections, pandas, seaborn, ranger, fasttext, re

Results Summary:

Data processing enabled successful price predictions with a exp-MSE of 0.067.  Furthermore, the use of pre-trained embedddings in place of categorical variables enabled 60% faster training while still maintaining high predictive power.

Files:
AirBnB-price-prediction.ipynb - provides a detailed look at all analyses performed on the AirBnB datasets.
