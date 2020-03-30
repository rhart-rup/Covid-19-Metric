# Covid-19-Metric

The number of **cases** of Covid-19 is an often quoted figure that is very probematic due to it's dependence on the testing regime within a country as well as the size of the country (larger countries are expected to have larger numbers of cases). 

An interesting and little seen metric for the Covid-19 outbreak is **daily deaths as a percentage of the population** - this highlights the recent acceleration in Covid-19 cases and allows us to more fairly compare different countries. We expect larger countries have larger healthcare capacities, so the percentage of deaths per population should provide a useful comparison for how much different countries are struggling. 

**In this notebook we calculate this metric for the accumulated deaths over the last 3 days and also plot this figure for daily deaths over the last 10 days. We express the metric in terms of deaths per million** 

An overview of the notebook is as below: 
1. Pulls **latest** data on Covid-19 cases and deaths from *European Centre for Disease Control*
2. Analyses and cleans the data
3. Calculates and plots the metric for the 20 countries with the largest value of the metric (in barplot) - the metric is calculated usng the last 3 days of deaths
4. Plots the evolution of the metric each day for the last 10 days in a line plot - the metric is calculatd using the daily deaths rather than last 3 days deaths
