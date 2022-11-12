# PyBer_Analysis

## Overview of the Analysis

Under this assignment, we intended to use more in depth the Pandas Python tools along with Matplotlib with the aim to analyze and to graph certain data. In this specific case a summmary DataFrame will be created using the ride-sharing data by city type, which file needs to be loaded into Jupyter Notebook to deliver the requested results:
-Summarizing how data differes by city type,
-how these data can give us information to help us make decisions related to this specific case.

## Results

The results of this assignment are going to be focused on two aspects. The firts one will be related to the analysis of the ride-sharing summary by city type; and the second one will be focus on graphing these data in a multi-line chart. Let's see what happened:

#### A ride-sharing summary DataFrame by city type.

As it can be seen in the file named -*PyBer_Challenge*-, output 131 in the Rural cities, despite having the less amount of drivers, they are the most well paid compared with Suburban and Urban cities. This results is a little counterproductive because if you compare quickly, whoever would think the drivers in the Urban cities are well paid compared to the other ones, but ii is not like that. This case should be given because we can infer the ride distance in the urban cities are shorter than the other ones, that's why this could cause this difference in the results. So one of the conclusion for this part would be to include the average ride distances on per driver, this way we could have more clarity to expose a more fair conclusion.

On the other hand, when the graph is seen here: 
![PyBer_fare_summary]

Within Rural cities, the fares received are less compared with Suburban and Urban cities, however is valid to highlight the end of month February all fares have a peak by those days, so it should be relevant to check what's happening around these days. 

As well, after April month, all fares tends to decrease except for Suburban cities where the tend continues almost constant or presenting an increment super slight.

## Summary

Given the results obtained in previous analysis, some recommendations can be shared with the CEO to address whatever issue he may have in this study. They are the following:

-Add to the data the distances per ride, in order to get the average distance driven by the drivers per day in each city. This way we can say if effective the productivity in the Rural cities is better than the other ones.
-Check the behavior, based on the attached graph, at the end of February month whre there is a peak on the fares value.
-what social phenomenon can be analyzed along the rides after April when Fares start decresing on Rural and Urban cities.


########--**Note: All the files have been uploaded to the GitHub repo as requested.**--
