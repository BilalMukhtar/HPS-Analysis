# HPS-Analysis
Utilizing vizualtion and modeling to understand booster rates

All data was sourced from the Household Pulse Survey Week 46 (https://www.census.gov/programs-surveys/household-pulse-survey/datasets.html)

This is a combination of two different projects from BMIS 2542 (Data Programming Essentials with Python)

## Vizualization
Determining the reasons why people who recieved at least one dose COVID-19 vaccine choose not to get a subsequent booster vaccination.

* Created maps using folium to find the states with the largest difference between vaccination and booster rate
* Displayed the reasons why people chose not to get the booster using bar graphs.

## Modeling
Determing the most important predictors in determing why people do not get the booster.

* Cleaned the data by removing outliers and predictors that had over 80% NA values
* Used forward selection to determine the predictors to be used in the models
* Utilized RandomForestClassifer to create the models
* Created confusion matrices to view accuracy of the models and importance graphs to present the most important predictors

