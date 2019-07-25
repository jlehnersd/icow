<center>
  <h1>
    Prediction of Attempts at Peaceful Resolution of Disputes Using the Issue Correlates of War Data Set 
  </h1>
  <h2>
    Jeremy Lehner
  </h2>
 </center>

------

------

## Motivation:

I would like to live in a world with less war. My dream is that one day, everyone lives in a world with no war (I'll go ahead and dream big on this one). The [Issue Correlates of War (ICOW)](https://www.paulhensel.org/icow.html) project tracks disputes over land, river, and sea territories from the 1800s to the 2000s. Among the ICOW data is the dyad-year data set, which describes all recorded dyadic disputes for each year from 1816 to 2001. I am interested in the outcomes of these disputes. How long do they last? How many lead to war? How many are settled without violence? To investigate these questions, I will use supervised machine learning to predict which disputes were attempted to be resolved peacefully. 



## Methodology:

1. Download ICOW csv data and import into a SQL database
2. Build binary response model
3. Classify disputes as having been attempted to be resolved peacefully or not
4. Analyze results to gain insights and stop war!



## Data Source:

- [Issue Correlates of War project](https://www.paulhensel.org/icow.html)



## MVP:

Predict whether or not there was an attempt at a peaceful resolution of a dispute in a given year.