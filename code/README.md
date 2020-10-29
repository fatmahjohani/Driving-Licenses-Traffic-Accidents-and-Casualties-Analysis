# Driving Licenses, Traffic Accidents and Casualties Analysis


## Problem Statement

Traffic accidents are a major Deaths reasons  in Saudi Arabia, and this  directly has increased markedly due to the increase in the number of road vehicles.
In This project, we're going to take a look at the number of traffic accidents and driving licenses issued in Saudi Arabia. Also, we will seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing the outcomes of traffic accidents in the various regions in Saudi Arabia.


## Executive Summary

The objective from this project is to figure out the relationship between traffic accident and driving licenses.
From this project we find out these key findings:
* Riyadh ranks first in the number of driving licenses in Saudi Arabia with 495307 licenses
* Makkah ranks second in the number of licenses issued in the kingdom with approximately of 157389 licenses.
* Madinah ranks 5th in the number of licenses issued in the kingdom with approximately of 36165 licenses.


## Datasets Description

In this project We have two Datasets:

[Driving Licenses](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&location=5,24.37495,45.08024&basemap=jawg.streets)
This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 1993 - 2016. Data from General Authority for Statistics . Follow datasource.kapsarc.org for timely data to advance energy economics research.

[Traffic Accidents and Casualties](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period)
This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2016. Data from General Authority for Statistics. Follow datasource.kapsarc.org for timely data to advance energy economics research.


##  Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Traffic_Accidents|This is the year when the accident happened|
|region|object|Traffic_Accidents|This is locate in which region the accident happened|
|indicator|object|Traffic_Accidents|This is identify the Number of Casualties and the condition (Dead or Injured)|
|value|int|Traffic_Accidents|This is the number of accidents|
|geopoint|int|Traffic_Accidents|This is holds geographic point coordinates|
|year|int|Driving_Licenses|This is the year when the Licenses issued|
|region|object|Driving_Licenses|This is the year where the Licenses issued|
|driving_licenses|int|Driving_Licenses|This is the Licenses number |
|geopoint_lic|object|Driving_Licenses|This is holds geographic point coordinates|
|x_Longitude|object|Driving_Licenses|sets the Latitude properties of geopoint|
|y_latitude|object|Driving_Licenses|sets the Longitude properties of geopoint|


## Conclusions and Recommendations

Based on the data given, we still missing number of accidents before 2016. However, we can come up with these recommendations.
Bellow are set of recommendations to reduce the Traffic accidents:
1. Set a Strict laws and expensive Fines for traffic violations.
2. Increase the Awareness of the Traffic systems
3. since the women in Saudi Arabia are still new to driving make a special programs targeting them.
Bellow are set of recommendations to reduce the Traffic accidents:

Set a Strict laws and expensive Fines for traffic violations.
Increase the Awareness of the Traffic systems
since the women in Saudi Arabia are still new to driving make a special programs targeting them.

## Authors

* **Fatimah Aljohani** - *Initial work* - [FatimahAljohani](https://git.generalassemb.ly/fatmahaljohani)

## Reference

[nytimes](https://www.nytimes.com/2019/06/24/world/middleeast/saudi-driving-ban-anniversary.html)
[sayidaty](https://cars.sayidaty.net/node/12561/)
[moi.gov.sa](https://www.moi.gov.sa/wps/portal/Home/sectors/publicsecurity/traffic/contents/!ut/p/z1/pVPLbsIwEPyVcugRef0gCUcX0jhAiwIKEF-q1E1at-QBjdLH19dwQCotBMSe1tLsrGc8RhItkMzjWj_HlS7yeGnOkbQewGdMYEaGXj_oAA-G7tjvUwIuoPkW0A28nhAbAOYWcN8mY_A72PMJkqfM7wDAnVvgnM6EsAMyHp443_O4YPYIwBl5HfC5CCfdgFLg9MT9B4pD0_wMSSRVXpXVC4qqdZymWl3DrslinV9DrYvl1tGrMjGuVjp534yVSj-hyGaUxhYAYxa2sbJiRUmqEqoINq2y9y36ewd5XMF8s6vBpCYO-duHf57pKMDB-4A9FZygyMi0D8vEaF7r5AOFebHOTDKnZzgooIndvoD9OHVILqAeNMXP_E_9ulpJbkJY5FXyWaHFOSmcJjkqs9BU5tCv9tvETe9cyqJB_X1z35aPjLdaP3rWooE!/dz/d5/L2dBISEvZ0FBIS9nQSEh/)
[middleeast](https://www.nytimes.com/2019/06/24/world/middleeast/saudi-driving-ban-anniversary.html)

## medium Blog Reference
[medium Blog](https://medium.com/@fatmah.aljohani/driving-licenses-traffic-accidents-and-casualties-analysis-74c540d6d08f)
