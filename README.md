# Dutch-Controversy-Detection

Indicator:Descriptive.ipynb takes in 10 csv files containing 1k of news posts of 10 different Dutch news outlets. Combines the files into one csv file, calculates entropy and runs a descriptive and length analysis. It appends source name to the content to capture source in word embedding and saves back to csv file : 'Indicator-Desc_Data.csv'.

Other files run XGBoost, Linear Regression, Random Forest, SVR and Language Model based on the word embedding choice. 
