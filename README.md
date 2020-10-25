# CropPrediction
Predicts the crop to be grown on a soil using ML.

1. Data Collation:
                   At first the Air humidity, Air temperature, Soil moisture, Soil pH and the GPS sensor modules are integrated with the NodeMCU platform into a portable kit. This                    kit is installed in the farm to gather the respective data of the soil. The data gathered is transferred in real time to firebase database for storage and                          further processing.
                   The atmospheric humidity, temperature, soil moisture, soil pH are sent as it is to the database. The latitude and longitude sent by the GPS module is retrieved                    in the form of which state they fall under. This enables us to collect the rainfall of that place in the previous year.
Data Processing Using Machine Learning
Crop Prediction:
Price Prediction:
