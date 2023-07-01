# Prediction-of-Engine-Health

Telematics systems can monitor the health of vehicles by collecting data on engine performance, battery status, tire pressure, and other critical parameters. By applying data analytics techniques, companies can predict maintenance needs, schedule repairs proactively, and minimize downtime.

## Features
The various features of the dataset are explained below:
Engine RPM (Revolutions Per Minute): Engine RPM refers to the number of revolutions the engine's crankshaft makes in one minute. 

Lub Oil Pressure: Lubricating oil pressure is the pressure of the oil circulating through the engine to provide lubrication to moving parts. 

Fuel Pressure: Fuel pressure refers to the pressure at which fuel is delivered to the engine for combustion. 

Coolant Pressure: Coolant pressure refers to the pressure of the coolant circulating through the engine to regulate its temperature.

Lub Oil Temperature: Lubricating oil temperature is the temperature of the engine oil.

Coolant Temperature: Coolant temperature refers to the temperature of the engine coolant.

Engine Condition: The engine condition parameter provides an indication of the overall health or condition of the engine. 

## Exploratory Data Analysis
![image](https://github.com/SumanVSarawad/Prediction-of-Engine-Health/assets/118813644/30bd939b-b932-4f82-a167-9b63b427e952)
![image](https://github.com/SumanVSarawad/Prediction-of-Engine-Health/assets/118813644/199c03ad-a020-4d37-9a9c-efb9c8674379)

## Feature Engineering
![boxplots](https://github.com/SumanVSarawad/Prediction-of-Engine-Health/assets/118813644/dcc5725b-538f-4507-b1b8-a2ad4f2b3b68)
As observable, there are many outliers in the data. We will do an outlier analysis using Z score for the coolant temp column and IQR method for the rest. 

The no. of outliers in Engine rpm is 464
The no. of outliers in Lub oil pressure is 66
The no. of outliers in Fuel pressure is 1135
The no. of outliers in Coolant pressure is 785
The no. of outliers in lub oil temp is 2617

## Results
LogisticRegression 
Accuracy Score: 65.06961506961507
F1 Score: 0.7564944333428489

Random Forest Classifier 
Accuracy Score: 64.78296478296478
F1 Score: 0.7407295749170938

Random Forest Classifier Hyperparameter tuning
Accuracy Score: 66.21621621621621
F1 Score: 0.7622478386167146

