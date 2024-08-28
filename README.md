## Dataset Description and Understanding
The dataset "contains the responses of a gas multisensor device deployed on the field in a significantly polluted area within an Italian city" (Vito). Hourly response averages were recorded along with gas concentrations from a certified analyzer, and the data was recorded from March 2004 to February 2005. The variables in this dataset include "ground truth hourly averaged concentrations for Carbon Monoxide, Non-Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides, and Nitrogen Dioxide" along with Relative Humidity (RH), Actual Humidity (AH), and Temperature (Celsius). There are 15 total variables and 9358 data points along with multiple missing values including some that are represented by the value -200.

Dataset Citation: Vito, Saverio. (2016). Air Quality. UCI Machine Learning Repository. https://doi.org/10.24432/C59K5F.

## Identification of Tasks
The regression task is to predict the temperature in the Italian city by using other variables that are useful in making this prediction.

### Possible predictors that could be helpful (input variables):
1. Date: (DD/MM/YYYY)
2. Time: (Hours)
3. CO(GT): Hourly averaged concentration CO in mg/m^3
4. PT08.S1 (Tin Oxide): Hourly averaged sensor response (CO targeted)
5. NMHC(GT): Hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 6. C6H6(GT): Hourly averaged Benzene concentration in microg/m^3
7. PT08.S2 (Titania): Hourly averaged sensor response (NMHC targeted)
8. NOx(GT): Hourly averaged NOx concentration in ppb
9. PT08.S3(NOx) (Tungsten Oxide): Hourly averaged sensor response (NOx targeted)
10. NO2(GT): Hourly averaged NO2 concentration in microg/m^3
11. PT08.S4 (tungsten oxide) Hourly averaged sensor response (NO2 targeted) 12. PT08.S5 (Indium Oxide): Hourly averaged sensor response (O3 targeted) 13. RH: Relative Humidity
14. RH: Absolute Humidity

### Response (output variable):
1. T: Temperature in °C
