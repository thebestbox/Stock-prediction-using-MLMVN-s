# Stock-prediction-using-MLMVN-s
The goal of this project is to build a program which when given 6 months of highs and lows of stock data it will train and optimize 150 neural networks, 50 trained on 1 month of data, 50 on 2 months of data and 50 on 3.
Using the results from the networks a basic trade risk algorithm will be implimented based off of the std. dev. and abverage of the predictions to allow for optimized trades over the next week. 
The networks will be real values where the output layer will have the function chosen during the optimization process. While the networks can be used for really any real valued regression data, the data shown will be on the dow jones index.
