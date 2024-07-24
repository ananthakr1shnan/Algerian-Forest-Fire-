# Algerian Forest Fires -FWI Prediction

## Introduction

This project usess a dataset from UCI on Algerian Forest Fires, including data from two regions in Algeria: Bejaia and Sidi Bel-Abbes. The dataset spans from June 2012 to September 2012. My objective is to explore the application of Machine Learning algorithms to predict fire weather index in these regions based on specific weather features.

## Data Set Information

The dataset includes 244 instances, with data collected from the Bejaia region (northeast Algeria) and the Sidi Bel-Abbes region (northwest Algeria), each contributing 122 instances. The dataset covers:

- **Time Period**: June 2012 to September 2012
- **Attributes**: 11 attributes plus 1 output attribute (class)
- **Classes**: Instances are categorized as fire (138) and not fire (106).

## Attribute Information

1. **Date**: (DD/MM/YYYY) Day, month ('June' to 'September'), year (2012)
2. **Weather Data Observations**:
   - **Temp**: Noon temperature (max) in Celsius: 22 to 42
   - **RH**: Relative Humidity in %: 21 to 90
   - **Ws**: Wind speed in km/h: 6 to 29
   - **Rain**: Total daily rainfall in mm: 0 to 16.8
3. **FWI Components**:
   - **FFMC**: Fine Fuel Moisture Code index: 28.6 to 92.5
   - **DMC**: Duff Moisture Code index: 1.1 to 65.9
   - **DC**: Drought Code index: 7 to 220.4
   - **ISI**: Initial Spread Index: 0 to 18.5
   - **BUI**: Buildup Index: 1.1 to 68
   - **FWI**: Fire Weather Index: 0 to 31.1
4. **Classes**: Fire and Not Fire

## Project Steps

1. **Data Collection**
2. **Data Pre-Processing**
3. **Exploratory Data Analysis**
4. **Feature Engineering**
5. **Feature Selection**
6. **Model Building**

## Model Building

### Regression Analysis

For regression analysis, the Fire Weather Index (FWI) was selected as the dependent feature due to its strong correlation (over 90%) with the classes variable. The following models were utilized:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression

### Flask application

To run flask app

```bash
python application.py

