# Covid 19 Severity Metric

This notebook attempted to test a new high level metric top measure the severity of the Covid-19 Pandemic in March 2020. The metric was found to be a poor measure, but was an interesting experiment none the less. 

## Motivation for Metric

The number of **cases** of Covid-19 is an often quoted figure that is very probematic due to it's dependence on the testing regime within a country as well as the size of the country (larger countries are expected to have larger numbers of cases). 

An interesting and little seen metric for the Covid-19 outbreak is **daily deaths as a percentage of the population**. This highlights the recent acceleration in Covid-19 cases and allows us to more fairly compare different countries. We expect larger countries have larger healthcare capacities, so the percentage of deaths per population should provide a useful comparison for how much different countries are struggling. 

## Summary of Notebook

In this notebook we calculate our metric for the accumulated deaths over the last 3 days and also plot this figure for daily deaths over the last 10 days. We express the metric in terms of deaths per million. 

An overview of the notebook is as below: 
1. Pulls **latest** data on Covid-19 cases and deaths from *European Centre for Disease Control*
2. Analyses and cleans the data
3. Calculates and plots the metric for the 20 countries with the largest value of the metric (in barplot) - the metric is calculated usng the last 3 days of deaths
4. Plots the evolution of the metric each day for the last 10 days in a line plot - the metric is calculatd using the daily deaths rather than last 3 days deaths

## Conclusions

The metric was found to be a poor measure that unfairly diluted the metric for countries with large populations and punished those with smaller populations e.g. Belgium. Fundamentally, the number of deaths and rate of deaths a country suffers is not driven by the countries population, rather it is almost entirely driven by the population density. The rate of spreading the disease and death therefore does not depend on population - China for example has a huge population and very small number of deaths (note that lockdowns act to artifically lower the population density, and therefore keep deaths low).

Simply looking at total deaths can be a good high level indicator of the severity of Covid facing a country. 

 

