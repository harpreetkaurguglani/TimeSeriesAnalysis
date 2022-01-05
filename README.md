# TimeSeriesAnalysis

Predictive analytics is a form of advanced analytics that uses both the new and the historical data to forecast the unforeseen events by carefully analyzing the behavior and the trend of the past observations. Although predictive analytics is an area of data mining which deals with extracting useful information from the collected observations and using this extracted information to predict the trend that might prevail in the near future. In the era of Big Data, time series modeling and forecasting are the cornerstones of predictive analytics. The processing of the model is done by formulating the past recorded equally spaced with time observations, and then exploring such formulated occurrences with an objective of prediction of the unknown future events.

Box-Jenkins’s forecasting techniques are used for the purpose of short-term prediction of the rainfall patterns for the capital of India, Delhi. For this purpose, the behavior and the seasonal trend of the data were captured and analyzed using historical twelve years and seven months of monthly average rainfall data of Delhi for the period January 2006 to July 2018. The data was obtained from the Indian Agriculture Research Institute (IARI). The modeling throughout the study was developed using SARIMA and the Holt-Winters additive method of time series and further, a comparative study was also conducted between the models obtained from both the methods.

## Objective
The aim of conducting the research is to identify the most apt model and obtain forecast from the selected model using time series analysis`s non-invasive techniques. 

## Study Analysis
The accuracy of the predicted model was compared using RMSE, MAE, and the ADF test. Based on the study, conclusion was drawn that the SARIMA model gave the most apt short-term forecasting model of the rainfall for the next two years for the capital, Delhi. The monthly data used for conducting the study was obtained from the Indian Agriculture Research Institute. The collected data has a total of 151 data points, spanning from January 2006 to July 2018. The average precipitation rate for this entire period is calculated to be 72.91mm and the data ranges from 0mm to 540.9mm of rainfall.

## Conclusions
This would discuss the area of predictive analytics and few of its methodologies that can be performed for conducting such analytics. It also discusses the process of data processing. Two forecasting methods -SARIMA and Holt-Winters additive were used and the forecasts were generated using the R software [22, 19]. The appropriate SARIMA model is (2, 0, 2)(2, 2, 1)12 and the Holt-Winter`s selected model is with the values of parameters as Alpha = 0.0285, Beta = 0, Gamma = 0.0001. Comparing the values of accuracy measures from both the models one can conclude that the prediction from the SARIMA is always better than the Holt-Winters predictions. These forecasting algorithms may also be applied to many different areas such as Banking and Financial Service, Health Insurance, Manufacturing, Prediction of the temperature to name a few.

**Data cannot be shared due to privacy policy.
