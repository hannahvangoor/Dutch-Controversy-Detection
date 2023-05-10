# Dutch-Controversy-Detection

Indicator:Descriptive.ipynb takes in 10 csv files containing 1k of news posts of 10 different Dutch news outlets. Combines the files into one csv file, calculates entropy and runs a descriptive and length analysis. It appends source name to the content to capture source in word embedding and saves back to csv file : 'Indicator-Desc_Data.csv'.

Pipeline_LR.ipynb explores a few ways of text vectorization, of which transformers with model bert-base-dutch-cased seems to work best. It then runs a simple linear regression on the word embeddings. 

Pipeline_Regressors.ipynb runs XGBoost, Random Forest and CatBoost on the word embeddings. 
