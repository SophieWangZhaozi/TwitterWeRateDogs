# US Airports On-time Performance
## by Sophie Wang


## Dataset

> There are two sources of data used and wrangled in my exploratory data analysis. The first one is downloaded on-time performance datasets from Jan to Mar in 2019 provided on Bureau of Transport Statistics https://www.transtats.bts.gov/DL_SelectFields.asp
The second one is wikipedia https://en.wikipedia.org/wiki/List_of_airports_in_the_United_States where one can exctract information about airports' size category according to FAA denifitions. 


## Summary of Findings
All findings below concern all US domestic flights scheudled for the first quarter of 2019.
> 1) The distribution of delayed flights is unimodel and right-skewed. The most common delay time is roughly 25 minutes. Number of flights gradually decreases after delayed for more than 50 minutes. Majority of delayed flights are late for under an hour. It's very rate for a flight to be late for more than 2 hours.
>2) Late aircraft arrival is the major reason for delay, followed by carrier-related issues such as maintenance or operations. Weather and security problems, interestingly, cause very few late departures.
>3) However, weather is a key reason for flight cancellations, causing roughly 63% of the total cancelled flights.
>4)Delayed flights represent 20% of total domestic flights, which means 80% of the flights are on-time.
>5) The average delay time by late aircraft arrival is 35 minutes, compared with 27 minutes by carrier_related issues, 14 minutes by National Air System caused problems and only 5 minutes by weather.
>6) Flights with a scheduled departure time around 5am suffer the longest delay time on average. This is true in each month of the first quarter. Delay time in peak travel hours (9am to 9pm) is consistent at roughly 75 minutes.
>7) Monday flights suffer the longest average delay. 
>8) Chicago O'Hare saw the highest number of delayed flights among all airports in the US, followed by Atlanta and Dallas Fortworth.
>9) Airport size doesn't seems to have an impact on on-time performance.
>10) The most punctual large airport in the US is Honolulu. In the medium and small size categories, winners are Anchorage and Hilo respectively. All of the three airports are not attached to the 48 states in North America.
>11) Two least punctual large airports serve New York while the other two serve Chicago. The remaining one is SFO. 
>12) Hawaiian Airlines, Spirit and Delta Air Lines are the top three on-time carriers in the US.


## Key Insights for Presentation

> Among all the findings, I hope to pick 2-3 to give a descriptive summary of US airports on-time performance in the first quarter of 2019. To this end, I will start by an overall stats on number of on-time vs. delayed flights. Then move on to focus on major reasons behind delay with histogram on distribution of the flights by delay time and barplot of average delay time by cause.
I will list top/bottom 5 airports in terms of on-time performance, followed by ranking of carriers.
I want the presentation to be straightforward but informative. Major difference between EDA and presentation is the style and the flow. While EDA doesn't follow a thread, presentation does. And the plots in the presentation are polished.
