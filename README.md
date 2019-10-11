# Project 2 - Ames Housing Data and Kaggle Challenge

This project is a part of the curriculum for General Assembly Data Science Immersive.

#### -- Project Status: [Completed]

## Problem/Objective
The problem this project aims to address is to advise Ames residents which particular features of a house will drive a house price up or down during sale. 

The purpose of this project is to explore the data obtained from Ames to prospect which features of the house best influence the price of the house.

### Methods Used
* Data Cleaning Methods
*  Statistical Inference
* Imputation of Missing Data
* Data Scaling
* Basic Modelling techniques
* Regularisation 
* Data Visualization

### Technologies
* Python
* Pandas, jupyter, numpy, scipy
* Matplotlib, Seaborn
* Scikit Learn

## Project Description
- Data was obtained from instructors and cleaned using these sources:
- <https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/submissions>[here]

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- missing data imputation
- statistical modeling
- writeup/reporting

## Getting Started

1. Please clone this repository before using it. 
2. Datasets are kept in .csv files that are contained in [../code/]within this repo.   
3. Data processing/transformation scripts are being kept [../code/]


## Resulting Data Dictionary

### Final Dataframe
|Feature|Type|Description|
|---|---|---|
|'overallqual'|Continuous| Overall material and finish quality|
|'masvnrarea'|Continuous|Masonry veneer area in square feet|
|'poolarea'|Continuous| Pool area in square feet|
|'fireplaces'|Continuous| Number of fireplaces|
|'grlivarea'|Continuous| Above grade (ground) living area square feet|
|'screenporch'|Continuous| Screen porch area in square feet|
|'lotarea'|Continuous| Lot size in square feet|
|'3ssnporch'|Continuous| Three season porch area in square feet|
|'bsmtfullbath'|Continuous| Basement full bathrooms|
|'totalbsmtsf'|Continuous| Total square feet of basement area|
|'garagearea'|Continuous| Size of garage in square feet|
|'yearbuilt'|Continuous| Original construction date|
|'exterqual_Fa'|Dummy| Exterior material quality_Fair|
|'exterqual_Gd'|Dummy| Exterior material quality_Good|
|'exterqual_TA'|Dummy| Exterior material quality_Average/Typical|
|'kitchenqual_Fa'|Dummy| Kitchen quality_Fair|
|'kitchenqual_Gd'|Dummy| Kitchen quality_Good|
|'kitchenqual_TA'|Dummy|Kitchen quality_Average/Typical|
|'bsmtqual_Fa'|Dummy| Height of the basement_Fair|
|'bsmtqual_Gd'|Dummy| Height of the basement_Gd|
|'bsmtqual_Po'|Dummy| Height of the basement_Po|
|'bsmtqual_TA'|Dummy| Height of the basement_Average/Typical|
|'garagefinish_RFn'|Dummy|  Interior finish of the garage_ Rough Finished|
|'garagefinish_Unf'|Dummy|  Interior finish of the garage_ Unfinished|
|'masvnrtype_BrkFace'|Dummy| Masonry veneer type_Brick Face|
|'masvnrtype_None'|Dummy| Masonry veneer type_ None|
|'masvnrtype_Stone'|Dummy|Masonry veneer type_Stone|
|'heatingqc_Fa'|Dummy| Heating quality and condition_ Fair|
|'heatingqc_Gd'|Dummy|Heating quality and condition_ Good|
|'heatingqc_Po'|Dummy|Heating quality and condition_ Poor|
|'heatingqc_TA'|Dummy|Heating quality and condition_ Average/Typical|
|'neighborhood_Blueste'|Dummy|Physical locations within Ames city limits Bluestem|
|'neighborhood_BrDale'|Dummy| Physical locations within Ames city limits Briardale|
|'neighborhood_BrkSide'|Dummy| Physical locations within Ames city limits Brookside|
|'neighborhood_ClearCr'|Dummy|Physical locations within Ames city limits Clear Creek|
|'neighborhood_CollgCr'|Dummy|Physical locations within Ames city limits College Creek|
|'neighborhood_Crawfor|Dummy|Physical locations within Ames city limits Crawford|
|'neighborhood_Edwards'|Dummy|Physical locations within Ames city limits Edwards|
|'neighborhood_Gilbert'|Dummy|Physical locations within Ames city limits Gilbert|
|'neighborhood_Greens'|Dummy| Physical locations within Ames city limits Greens|
|'neighborhood_IDOTRR'|Dummy|Physical locations within Ames city limits IOWA Dot and Railroad|
|'neighborhood_MeadowV'|Dummy| Physical locations within Ames city limits Meadow Village|
|'neighborhood_Mitchel'|Dummy| Physical locations within Ames city limits Mitchell|
|'neighborhood_NAmes'|Dummy| Physical locations within Ames city limits North Ames|
|'neighborhood_NPkVill'|Dummy| Physical locations within Ames city limits Northpark Villa|
|'neighborhood_NWAmes'|Dummy| Physical locations within Ames city limits Northwest Ames|
|'neighborhood_NoRidge'|Dummy| Physical locations within Ames city limits Northridge|
|'neighborhood_NridgHt'|Dummy| Physical locations within Ames city limits Northridge Heights|
|'neighborhood_OldTown'|Dummy| Physical locations within Ames city limits Old Town|
|'neighborhood_SWISU'|Dummy| Physical locations within Ames city limits South & West of Iowa State University|
|'neighborhood_Sawyer'|Dummy| Physical locations within Ames city limits Sawyer|
|'neighborhood_SawyerW'|Dummy| Physical locations within Ames city limits Sawyer West|
|'neighborhood_Somerst'|Dummy| Physical locations within Ames city limits  Somerset|
|'neighborhood_StoneBr'|Dummy|Physical locations within Ames city limits  Stone Brook|
|'neighborhood_Timber'|Dummy|Physical locations within Ames city limits Timberland|
|'neighborhood_Veenker'|Dummy| Physical locations within Ames city limits Veenker|
|'paveddrive_P',|Dummy| Partial Paved Drive|
|'paveddrive_Y',|Dummy| Paved Drive|
|'lotshape_IR2',|Dummy| General shape of property_Moderately Irregular|
|'lotshape_IR3',|Dummy|General shape of property_Irregular|
|'lotshape_Reg'|Dummy|General shape of property_regular|

