# LifeExpectancyVsTime
The analysis uses the gapminder dataset to analyze life expectancy over time. It performs various data manipulations and visualizations using dplyr and ggplot2 libraries in R.

The steps involved in the analysis are as follows:

1. Load the gapminder dataset.
2. Calculate the mean and standard deviation of life expectancy for each continent-year.
3. Plot the mean life expectancy as a line graph.
4. Plot the standard deviation of life expectancy as a ribbon.
5. Facet the plots by continent.
6. Plot individual country-year values of life expectancy as points on a plot.
7. Filter out the countries in the top or bottom 20% of observations of life expectancy for each continent-year.
8. Plot the remaining countries.
9. Calculate the distance between individual country-year values and the continent-year mean for life expectancy.
10. Vary the transparency of the points based on the variance from the continent-year mean of life expectancy.
11. Calculate the mean total population for each continent-year.
12. Create a binary variable that indicates whether the given country-year has a population above or below the mean population for the continent-year.
13. Color the points according to the population analysis variable.

The analysis uses visualizations like line graphs, ribbon plots, and facet plots to explore the trends and patterns in life expectancy over time for different continents, and also considers the population analysis in relation to life expectancy.
