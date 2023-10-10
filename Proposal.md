---
output:
  pdf_document: default
  html_document: default
---
# TITLE

FORECASTING ENERGY CONSUMPTION

## NAMES

Swetha Siripurapu, Shalon Walter

# INTRODUCTION

Climate change is a critical global issue caused by excessive greenhouse gas emissions from various human activities. Among these activities, energy consumption is the primary contributor to greenhouse gas emissions. Cooling and heating buildings account for a significant portion of these emissions, and with the global demand for cooling tripling since the 1980s, it is crucial to regulate energy consumption through suitable models and optimize HVAC systems to reduce carbon footprint.  


# PROBLEM SETTING

The rise in greenhouse gas emissions due to excessive energy consumption is alarming, with buildings accounting for 28% of total emissions. This calls for identifying suitable models to predict energy consumption and optimize HVAC systems to lower carbon emissions.


# PROBLEM DEFINITION

This project aims to identify the most appropriate classification and regression models to predict energy consumption in buildings, specifically through HVAC systems (Heating, Ventilation and Air Conditioning Systems). By analyzing patterns in energy consumption, this project intends to optimize HVAC systems and reduce the carbon footprint. The dataset used includes energy consumption data from 1000 buildings over three years, with key features consisting of data related to weather, meter type, and building descriptions. The ultimate goal is to reduce the carbon impact on the environment, contributing to a more sustainable future.

# DATA SOURCE CITATION

This dataset is a reference from Kaggle competition:  
Source: https://www.kaggle.com/c/ashrae-energy-prediction/overview

# DATA DESCRIPTION

The data has over 1000 buildings over a time frame of 3 years, which contains the attributes which describes the building, meter category and weather details. It can be used to predict Energy consumption in kWh. We have 3 Files of data which is used for Analysis and Modeling.   

The dataset has 20 million records with 15 features.

Training dataset - 14,151,270 samples (70% of the data)  
Testing dataset - 6,064,830 samples (30% of the data) 

The Following are the Attributes and their descriptions:
•	building_id – Building Identifier  
•	meter – It is a code read as 0: Electricity, 1: Chilledwater, 2: Steam, 3: Hotwater.  
•	meter_reading – Energy Consumption is kWh, Considered as Class Label/Target Label.  
•	timestamp – Time and Date when measurements are taken.  
•	site_id – Identity for Weather files.  
•	primary_use – Specifies the category for which the building is used.  
•	Square_feet – Floor area of the building.  
• Year_built – Year in which git  building was built.  
•	floor_count – Indicates the ncdumber of floors in a building.  
• air_temperature – Measure of Temperature in Degree Celsius.  
•	cloud_coverage – Amount of cloud cover at given location in okta.  
•	dew_temperature – Temperature in Degree Celsius.  
•	Precip_depth_1_hr – Precipitation depth for 1 hour in Millimeters.  
•	sea_level_pressure – Sea Level Pressure in Millibar/Hectopascals.  
•	wind_direction – Direction of wind in Compass (0-360o).  
•	wind_speed – Speed of Wind in Meters per second.

# WHAT HAS BEEN PREVIOUSLY DONE IN THIS FIELD?

Although energy consumption has been extensively studied in the field of computer architecture for many years, the adoption of energy as a metric in machine learning research is still emerging. Most of the current research in machine learning focuses on achieving high levels of accuracy without considering computational constraints. This lack of interest in energy consumption may be due to a lack of understanding of how to evaluate it.To address the challenge, we researched methods for estimating energy consumption in machine learning applications. Our research exposed us to  various approaches for estimating energy consumption in both general and machine learning contexts. Our goal is to develop a model with better accuracy from the ones that have already been developed. We plan to achieve this by feature engineering, hyper parameter tuning and ensemble methods. 

# HOW IS THIS DIFFERENT FROM THE ONE IN KAGGLE COMPETITION.

Previous models have focused on predicting energy consumption, optimizing energy efficiency, forecasting renewable energy, and detecting energy faults using various machine learning techniques such as regression analysis, artificial neural networks, decision trees, and support vector machines. However, our project focuses on using four specific machine learning algorithms: Linear Regression, Long-Short Term Memory (LSTM), Support Vector Machine (SVM), and Random Forest. These algorithms are well-suited for analyzing complex and large data sets, and we believe that by using them, we can achieve more accurate energy consumption predictions and provide better insights for energy management.

# MACHINE LEARNING ALGORITHMS

These are the Machine Learning Algorithms we are planning to use:  
1.	Linear Regression.  
2.	Long-Short Term Memory (LSTM).  
3.	Support Vector Machine (SVM).  
4.	Random Forest.  

# LIST OF QUESTIONS AND OBJECTIVES OF OUR PROJECT

## Motivation to select this topic:

•	What are the current trends in energy consumption in our target population?  
•	How does energy consumption impact the environment and climate change?  
•	How can we encourage more sustainable energy consumption habits?  

## Trying and choosing best model type:

•	Which model type is best suited to predicting energy consumption data?  
•	How do we balance model accuracy with interpretability?    

## Use the best predictors from the dataset:

•	Which variables in the dataset are the strongest predictors of energy consumption?  
•	How do we handle missing or incomplete data?

## Analysis methods to predict future energy consumption:

•	Which machine learning algorithms or statistical models can be used to predict future energy consumption?  
•	How do we measure model performance, such as Mean Absolute Error or Root Mean Squared Error?  
•	How do we handle potential biases in the data, such as seasonality or outliers?  

Overall, the goal of this analysis would be to better understand energy consumption patterns and identify opportunities for promoting more sustainable behavior, while also predicting future trends with greater accuracy



