## SRC

### Installing/Building Code

The code is in the Jupyter Notebook (.ipynb file format). It can be run locally using software such as Jupyter Labs or VSCode, or in the cloud using a service such as Google Colab.

### Usage of Code

The Canada_Temperature_Models.ipynb file is used for our machine learning models of prediction and the Final.ipynb is used for our SARIMA model of prediction.

## DATA

### Data Dictionary
| Variable | Description |
| -------- | ----------- |
| LOCAL_DATE | Date that the measurement was taken |
| MEAN_TEMPERATURE_CALGARY | Average temperature in Celsius in Calgary, Canada on the specified date |
| MEAN_TEMPERATURE_VANCOUVER | Average temperature in Celsius in Vancouver, Canada on the specified date |
| MEAN_TEMPERATURE_WINNIPEG | Average temperature in Celsius in Winnipeg, Canada on the specified date |
| MEAN_TEMPERATURE_TORONTO | Average temperature in Celsius in Toronto, Canada on the specified date |
| MEAN_PRECIPITATION_CALGARY | Average precipitation in millimeters in Calgary, Canada on the specified date |
| MEAN_PRECIPITATION_VANCOUVER | Average precipitation in millimeters in Vancouver, Canada on the specified date |
| MEAN_PRECIPITATION_WINNIPEG | Average precipitation in millimeters in Winnipeg, Canada on the specified date |
| MEAN_PRECIPITATION_TORONTO | Average precipitation in millimeters in Toronto, Canada on the specified date |

### Link to Data
[Our Data](https://github.com/jnm9aba/DS4002Project3/tree/main/DATA)

### Notes
A few dates are excluded from the data.

## FIGURES
| Figure | Takeaways |
| -------- | ----------- |
| LR_canada_temps.png | In our linear regression, temperatures went up and down over the years, which we would guess with seasons |
| RF_forecasted_temps.png | The random forest model tends to show predictions lower than actual temperatures before the prediction years |
| RF_predicted_temps.png | Our random forest predictions were fairly close to the actual temperatures |
| model_prediction.png | Our SARIMA model tended to do a fairly good job at predicting temperatures |


## REFERENCES
[1] E. and C. C. Canada, “Government of Canada,” Canada.ca, 09-Apr-2019. [Online]. Available: https://www.canada.ca/en/environment-climate-change/services/climate-change/canadian-centre-climate-services/basics/trends-projections/changes-temperature.html. [Accessed: 02-Nov-2022].

[2] E. and C. C. Canada, “Government of Canada,” Canada.ca, 07-Nov-2022. [Online]. Available: https://www.canada.ca/en/environment-climate-change.html. [Accessed: 09-Nov-2022].

[3] “Time Series Forecasting methods,” InfluxData, 19-Sep-2022. [Online]. Available: https://www.influxdata.com/time-series-forecasting-methods/. [Accessed: 09-Nov-2022]. 

[4] “Different types of time series decomposition.” [Online]. Available: https://towardsdatascience.com/different-types-of-time-series-decomposition-396c09f92693. [Accessed: 09-Nov-2022]. 

[5] “Time Series Forecast Error Metrics you should know.” [Online]. Available: https://towardsdatascience.com/time-series-forecast-error-metrics-you-should-know-cc88b8c67f27. [Accessed: 09-Nov-2022]. 

### Acknowledgements
We would like to acknowledge Professor Alonzi and Harsh for helping us throughout our project. 

### MI1 Assignment
[Milestone 1](https://docs.google.com/document/d/1I1iGIr0NDgdUJvNL1CdqgkITHBegzS7AKfov62luD8E/edit?usp=sharing)

### MI2 Assignment
[Milestone 2](https://docs.google.com/document/d/1OdormW_93K9oRIQghBU97yLtYs5PTN0QwMcOz4kYsP0/edit?usp=sharing)


