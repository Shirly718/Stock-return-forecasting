# Stock-return-forecasting
MPS Capstone Project at Cornell Unviersity
The goal of the project was to build on previous year Cornell MPS projects to predict returns for
a universe of stock and financial assets. We did not explore time series analysis in our model
research as our stock data failed to meet the stationarity and linearity assumptions required for
traditional time series models such as ARIMA. Instead, we mainly investigated and implemented
random forest and deep learning models that made use of Recurrent Neural Networks (RNN),
specifically LSTM.
In the following section, the report will detail data preparation and cleaning. Then section three
and four will discuss and implementation and evaluation of the random forest and long shortterm
memory (LSTM) models. The models were evaluated using Mean Squared Error (MSE) in
addition to cross validation and will be discussed in further detail. Finally, in section five, the
report will conclude with model limitations and possible steps to further improve model
performance.
