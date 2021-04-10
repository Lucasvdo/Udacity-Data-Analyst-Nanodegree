# Analyzing Spatial data from the GoFord bike sharing service¶
## by Lucas Valerio de Oliveira

## Introduction

According to Wikipedia, Ford GoBike is a public bike sharing system in California's San Francisco Bay region. Initially known as Bay Wheels, Ford GoBike is the first regional and large-scale bike-sharing system deployed in California and the west coast of the United States. It was established as bay area bike share in August 2013. As of January 2018, the Bay Wheels system had more than 2,600 bikes at 262 stations in San Francisco, East Bay and San Jose.

In this study, data provided by the bike sharing program during the period of February 2019 will be analyzed. The data will be analyzed through an exploratory analysis and finally an explanatory analysis of the data will be made.

## Dataset

The data has 183412 rows of records and 16 columns of data. Some tables have null data that needs to be analyzed to decide whether to be treated or remove. egarding the type of data, it is observed that date and time variables need to be treated for the DateTime type. Fields that have some ID identifier need to be converted to String, and finally the Birthday Year variable deve der analisada, uma vez que foi identificado individuos should be analyzed, since it was identified individuals who have a date of birth of 1878 and therefore we should analyze the case. Finally, the data are from the period of February 2019


## Summary of Findings

*  What interested me most in the data was the desire to find out how the data is distributed spatially and then build a real graphical representation of that distribution,we can use the LAT data, LONG for that.

* In addition, I will try to find out which factors influence the duration of the trip in terms of date and time, age of users, point of departure and point of arrival and also in relation to the gender of the user.

## Key Insights for Presentation

What is the distribution of spatial data?

What are the relationships between the macro areas and the time, user and travel variables?

What are the relationships between the micro areas with the time, users and travel variables?