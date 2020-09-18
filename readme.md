# Exploratory Analysis of Flights Data
## by Essien Daniel



## Dataset

> he Flights dataset report flights in the United States, including carriers, arrival and departure delays, and reasons for delays.The dataset considered is year 2008. It consist of 2389217 records and 29 features. 
> After data wrangling processes, the dimension of dataset used became 870780 records and 15 features which include  DepDelay, ArrDelay, State,Airport, Dest, Distance, Cancelled, UniqueCarrier, Month, DayofMonth, CancellationCode, CarrierDelay, WeatherDelay, NASDelay, SecurityDelay.

## Summary of Findings

> The key finding are:

* Arrival and departure delay time between 0 and 50 minutes occurred the most and more arrival delays between 300 and 400 minutes than departure delays in that same time range.

* **Southwest Airlines Co(WN)** had the most count followed by **Associated Aviation Act(AA)** while the least counts were **Hawaiian Airlines Inc(HA)** and **Aloha Airlines Inc(AQ)**

* Carrier and Weather delays were more within an hour compare to NAS and Security delays.

* **Hawaii(HI)** had the lowest arrival and departure delays while **South Dakota(SD)** have the highest arrival delays.

* Shorter distances experienced more arrival delays and the delays were intense within 100 minutes.

* Generally departure delays were directly proportional to arrival delays for the carriers which means that the more departure delays the more the arrival delays.

## Key Insights for Presentation

> The relationship between arrival delays, departure delays, airline carriers and state.

## Reference
* [How To Annotate Bars in Barplot with Matplotlib in Python? - Data Viz with Python and R](https://seaborn.pydata.org/tutorial/axis_grids.html)

* [Building structured multi-plot grids — seaborn 0.11.0 documentation](https://seaborn.pydata.org/tutorial/axis_grids.html)

* [seaborn.FacetGrid — seaborn 0.10.1 documentation](https://seaborn.pydata.org/generated/seaborn.FacetGrid.html)

* [What Is Seaborn in Python | Data Visualization Using Seaborn](https://www.analyticsvidhya.com/blog/2019/09/comprehensive-data-visualization-guide-seaborn-python/?utm_source=blog&utm_medium=6-data-visualization-python-libraries)

* [The Next Level of Data Visualization in Python | by Will Koehrsen | Towards Data Science](https://towardsdatascience.com/the-next-level-of-data-visualization-in-python-dd6e99039d5e)