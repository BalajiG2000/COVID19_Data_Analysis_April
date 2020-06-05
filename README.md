# COVID19_Data_Analysis_April


Through this project,I learnt how to preprocess and merge datasets to calculate needed measures and prepare them for an Analysis.

I worked with the COVID19 dataset, published by John Hopkins University, which consists of the data related to the cumulative number of confirmed cases, per day, in each Country. Also, I used another dataset consist of various life factors, scored by the people living in each country around the globe.

I merged these two datasets to see if there is any relationship between the spread of the virus in a country and how happy people are, living in that country.


I calculated aggregate of infected persons Because in each row of the dataframe I had data related to each province in each country, but for the analysis I needed number of confirmed cases related to each country.


STEPS INVOLVED:


Importing COVID19 dataset and preparing it for the analysis by dropping columns and aggregating rows.


Deciding on and calculating a good measure for our analysis.


Merging two datasets and finding correlations among our data.


Visualizing the analysis results using Seaborn.



CONCLUSION:

Through the correlation matrix we found there is a positive correlation between max_infection_rate and all life factors . Thus we can conclude that in initial stages,people in developed countries are more prone to corona virus .

Their travel history across the world could be one of the reason.Also less number of test kits in developing countries too.
But during the later half ,Developing countries are getting severely affected.

Social distancing is practically impossible in crowded communities, health systems are ill-equipped, malnutrition and poverty are often widespread and vulnerable economies dependent on industries such as tourism will falter. 

Political instability, xenophobia and social unrest present additional risks as the coronavirus spreads.

