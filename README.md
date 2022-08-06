# Yulu-Hypothesis-Testing
# Yulu

Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting. 
Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!  

# Business Problem

Yulu have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.  
The company wants to know:  
1. Which variables are significant in predicting the demand for shared electric cycles in the Indian market? 
2. How well those variables describe the electric cycle demands?

# EDA Approach:

1. we will import the dataset and do exploratory data analysis steps like checking the structure & characteristics of the dataset.
2. we will try establishing a relation between the dependent and independent variable (Dependent “Count” & Independent: Workingday, Weather, Season etc)
3. we will use the Central limit theorem to compute the intervals of count amount depending on various weather, season, working day, etc.
4. We will perform the following hypothesis tests- 
 a) Working Day has effect on number of electric cycles rented
 b) No. of cycles rented similar or different in different seasons
 c) No. of cycles rented similar or different in different weather
 d) Weather is dependent on season (check between 2 predictor variable)
5. Inference from the analysis
