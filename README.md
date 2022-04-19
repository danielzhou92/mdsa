# MDSA (2021-2023) Project Descriptions

This repository is used to store my completed projects (mostly team projects) for the 2021-2022 University of Calgary Master of Data Science and Analytics Program.

[Program homepage](https://science.ucalgary.ca/data-science/programs/professional-programs/mdsa)

## [DATA601 - Working with Data and Visualization - Project Olympics (Oct 2021)](data601_project_olympics)

### Summer Olympic Games Analysis from 1896 to 2020

Using Python with Jupyter Notebook.

This notebook is explore and visualize the history of the Olympics from a country and medal standpoint.

some topics we explored are:
1. Which countries have hosted the most Olympics? Which continents have hosted the most Olympics?
2. Is there any relationship between being the host country and the number of medals one country won?
3. Which are the top countries based on the medals they have won? And is the medals tally related to the ecomony of the coutry?
4. Does political events affect the Olympic Games?


## [DATA602 - Statistical Data Analysis - Project Marathon (Oct 2021)](data602_project_marathon)

### Inferences on Marathon Runner Participation and Performance

Using R.

This paper attempts to draw relationships and predict performance between gender, age, and/or nationality of citizenship for competitive marathon runners.

Some inferences we explored are:
1. Does gender influence the mean marathon completion time? Does gender influence the variance of marathon completion time? Does age influence the mean marathon completion time?
2. Are the population proportions of men and women finishers equal across continents?
3. As the demographic of marathon runners is seemingly changing, does the age distribution of finishers reflect a normal distribution?
4. Can we establish a relationship between age and performance using simple linear regression?


## [DATA603 - Statistical Modeling With Data - Project Basketball (Dec 2021)](data603_project_basketball)

### NBA Player Point Per Game Multiple Linear Regression Modeling

Using R.

This project is to create a Multiple Linear Regression model for modeling points per game of an NBA player in a particular season where the player played 10 or more regular season games based on several independent variables, specifically these variables are:

* core player attributes:
    - age (at start of season)
    - height (at start of season)
    - weight (at start of season)
* other box score statistics:
    - total games played (at end of season)
    - average assists per game (at end of season)
    - average rebounds per game (at end of season)
    - average net rating (at end of season)
* round drafted in the NBA draft


## [DATA604 - Big Data Management - Project COVID (Dec 2021)](data604_project_covid)

### Effects of COVID-19 on Different Industries of Canada

Using SQL with MariaDB / Python with Jupyter Notebook.

This project is aimed to compare how the pandemic has affected some of the industries in Canada. Many industries have suffered while others flourished during the pandemic. 

There were 6 group members and we will be examining the following 6 domains to see if there are interrelated trends between the industries as well as to the severity of pandemic:

1. Tourism
2. Air travel
3. Ground travel
4. Electricity
5. Retail
6. Manufacturing

For my personal part, I used SQL queries with MariaDB along with Pandas and Plotly with Python to examine the Ground Travel Domain, which focuses on international ground travel at the Canada-US border, some of the research questions I answered are:

1. Did COVID-19 affect the number of vehicles crossing the border between Canada and United States?
2. If so, how does the effect on international ground travel differ at a provincial level?
3. Has vaccine helped with international ground travel numbers recovery?
4. Do different bordering countries affect ground travel impact and recovery differently?


## [DATA606 - Statistical Methods in Data Science - Project Hotel (Feb 2022)](data606_project_hotel)

### Hotel Booking Demand and Cancellation Analysis

Using R.

This project is to use various qualitative (binary and nominal) and quantitative variables (discrete and continuous) to build models that can predict hotel booking cancelations as well as buidling a model to predict average daily cost of a hotel stay.

There are 3 research questions analyzed in this report:

1. Using contingency tables, can it be determined if there is independence between categorical variables?
2. Which model is the best at predicting hotel booking cancellation in Portugal between:
    * Logistic Regression, 
    * Classification Tree, 
    * Random Forest Analysis, and 
    * Linear/Quadratic Discriminant Analysis.
3. Using regression tree, which variables are important in predicting average daily rate of a hotel stay in Portugal?


## [DATA607 - Statistical and Machine Learning - Project Plants (Apr 2022)](data607_project_plants)

### Classifying Plant Disease from Images Using Traditional ML Models and CNN

Using SKLearn and Pytorch in Python with Jupyter Notebook.

This project is to train and evaluate several different models to recognize plant diseases from images.

The models explored are:
1. Naive Bayes Classifier
2. Linear Support Vector Machine with Stochastic Gradient Descent Optimization
3. Random Forest Classifier
4. Gradient Boosting Classifier
5. CNN model trained from scratch
6. Transfer learning CNN model