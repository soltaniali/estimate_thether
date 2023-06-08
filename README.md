# estimate_thether
this a machine leraning estimation for the theter in toman , that i've used EDA , pre-proccessing and sampling &amp; in the using 3 models to learn and get the best resault i can .

in this project i first try to clean the data , with full the null value some times with median or avg . 
and some thimes i just delete some rows! 
then i added some features that may help me , like MACD , CCI and other binance features, for feature engineering.
and after that i do some EDA , like draw the correlation diagram and describe the DF and other things.
next i used PCA to get just usefull data to avoid models from overfitting and have lower cost to my resourcces.
i added some unsuperviesed features , i just used Kelbow to add some unvisioned feature the machine could get. 
After all i used the pycaret to get the estimations for models based on F1 point , 
and i choose top 3 to fit .
before fit the models i just grid use grid search on hyper - parameters to get best model i can , 
and in the end i just predict the data. 
Thank u for reading this ! :)
