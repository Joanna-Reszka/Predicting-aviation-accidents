# Predicting-aviation-accidents

## Can we use machine learning models to predict survivability of aviation accident based on dataset from US?
#### Exploratory data analysis and machine learning models on dataset from Kaggle:
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses
<br />
#### Team project at Data Science bootcamp at InfoShare Academy 
https://github.com/infoshareacademy/jdszr12-databenders

## Introduction



## Dataset

#### The NTSB aviation accident database contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters.

## Data cleaning, preparation and transformation

#### ### Inspecting database, cleaning and transforming data 
-  aligning misalligned rows,
-  deleting irrelevant columns,
-  converting date to datetime (year, month, weekday)
- cleaning and standardising names in columns (as much as possible):
   -  nr of engines
   -  amateur build
   -  make
   -  weather conditions
   -  broad phase of flight
   -  airport class
-  filling NA with UNKNOWN or 0
-  creating target column of nr of none, minor, serious or fatal injuries to binary column of none-minor or serious-fatal injuries
-  choosing subset of data limited to:
   -  country: US
   -  year: after 1982
   -  aircraft category: airplane and helicopter

## Questions

####  Can we use machine learning models to predict survivability of aviation accident based on dataset from US?
<br />  

## Insights from the exploratory data analysys 
###
### 1. Generations, types and combat statistics frequency distributions:


![image](https://github.com/Joanna-Reszka/World-of-Pokemon/assets/97312220/7a721e6a-e11c-49d3-a5c5-1b583ea8d0b4)

#### Almost 60 % of pokemon come from first, fifth and third generation, and only 20 % of pokemon come from sixth and seventh generation.

![image](https://github.com/Joanna-Reszka/World-of-Pokemon/assets/97312220/af328ac4-dfc7-40a7-a21e-4273dc9e3df4)

#### The proportion of single type versus double type pokemon is balanced, 52%  of pokemon are double typed and 48% are single type.

![image](https://github.com/Joanna-Reszka/World-of-Pokemon/assets/97312220/465e4ce6-c47d-4c09-a08d-1e56f9c1ee1b)

#### Most frequent types are *Water*, *Normal*, *Grass* and *Flying*. The least frequent types are *Ice*, *Ghost* and *Dragon*.



#### Weight and height are heavily right skewed with few extreme values on the right. Legendary pokemon seem to be enerally bigger (taller and heavier)


### General insights

#### Clearly 
    
### 3. Feature correlations




## Conclusions and reccomendations

#### The fascinating world of pokemon has revealed some of its secrets, but it would be interesting to check how the different strategies (balanced versus specialised) translate to combat skills, resiliancy and attack resistance.
