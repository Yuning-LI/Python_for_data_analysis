# ESILV - Python for data analysis - devoir 2021
## Submitted by Kanika Mahajan & Yuning LI

## 1.Task
The [Seoul Bike Sharing Demand Data Set](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand?fbclid=IwAR0kA9lVpTHUikp5xuQKmz9VVeHXeTDkNyON3PUMLqKE6UWB4iReOBS4fP0) is about the bike renting information. In different situation including Time, Temperature, Humidity etc, we have different bike rented number.
So our aim is to explore the relationship between bike rented number and other features, and build the model to help make prediction.

## 2.Process
### 2.1 Data visualization
visualize the basic information in the original dataset to have a better understanding, including the correlationship, changement, etc.
### 2.2 Data preparation for modeling
In order to do modelization,we should firstly prepare the data, including the missing value exclusion, changing data type, dropping the incorrect data, split the training set, etc.
### 2.3 Modelization and validation
try different regression models to predict the result, compare them and select the best algorithm, them optimize its parameter to get the best model.

## 3.Conclusion
Random forest regression has the best performance, we save the model into a separate file, and build the Flask API.
#### Attention please: the model is using sklearn version0.23, so if you are using other version, perhaps it can not predict when you run flask API and you need to reinstall sklearn0.23.2 please.

