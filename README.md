# Green-Energy
## This project uses the ML regression models to predict the PV power generated from a plant including the cost and savings during the operation.

##Developer: 
Sitara Wishal Fatima
This is an independent project, which takes the input data from weather and enviroment and predicts the energy yield for a Solar PV system in the US. 
 
##Data Sources:
- NSRDB (https://nsrdb.nrel.gov/)
- PV installations (https://openpv.nrel.gov/)

The data from the NSRDB is averaged over a year. 
##Feature Engineering:
Feature correlation and feature importance is used to extract the useful models for ML models training. 
Following numerical features have been used with the above mentioned datasets: 
- Size (kW)
- array tilt
- Temperature
- Wind Speed
- Azimuth
- Direct Normal Irradiance
- Direct Horizontal Irradiance 
##Predicted Ouput: 
Using the geographical location, panel size, roof pitch and its orientation the script provides predictions for:

* Annual Energy Output (kWh/year)
* Annual Return (CAD)
* Installation cost (CAD)
* Break Even Time (Years)
