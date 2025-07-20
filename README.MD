# 2015 Flight Delays and Cancellations

### Note: Data (openly available) for this analysis is obtained from this [link](https://www.kaggle.com/datasets/usdot/flight-delays?ref=hackernoon.com).

#### The goal of this analysis is to identify the most common causes of flight disruptions by studying the frequency of cancellations by airline.

**Power BI concepts used:**

* Power Query (Data Load and Transformation) - Merged day, month, and year columns to create a date field. Deleted additional columns which are (unnecessarily) adding to the size of the data.
* Measures and Standard Aggregations - Created additional columns with calculations to determine the distance buckets, and delay time buckets. Added few measures to calculate % of flights delayed, % of flights cancelled, and % of flights diverted. Quick measures used to create unfiltered aggregations to derive these measures accurately.
* Charts - Cards, Tables, Bar Chart, and pie charts are used to display necessary metrics.
* Drill Through Pages - Drill Through page is added to further understand the reasons for delays and calculations.

![2015 US Flight Delay Statistics](/2015_US_Flight_Delay_Stats.png)

![2015 US Flight Cancellation Statistics](/2015_US_Flight_Cancellation_Stats.png)

![2015 US Flight Diversion Statistics](/2015_US_Flight_Diversions_Stats.png)

![2015 US Flight - Reasons for Delays and Cancellations](/2015_US_Flight_Reasons_for_Delays&Cancellations.png)

[Access "Flights Delays and Cancellations (2015 US)" dashboard here](https://app.powerbi.com/groups/me/reports/2f63d05f-abe7-44b2-9d33-fd45df73221d/7fbb55f7b669ccf047e9?experience=power-bi)

#### Analysis outcomes as follows:

1. 18% of the flights are delayed for various reasons.
    a. "Southwest Airlines Co." is contributing to the highest number of delays (this is understandable, given the size of this airlines compared to others)
    b. "Late Aircraft" is the number one reason for delay across airlines (further information is need to analyze what exactly is causing this).
    c. More than 50% of the delays are within 15 minutes to 1 hour range.
    d. Often times, shorthauls are delayed compared to long range flight. 
2. 1.5% of total flights are subjected to cancellations. 
    a. Weather related reasons play major role in cancellations (understandably) followed by national air systems.
    b. Cancellations are very high during the month of February (due to fog?).
    c. Over 16K flights cancelled by Southwest Airlines Co. in the year of 2015.
3. Little over 0.2% flights are diverted in the year of 2015. Reasons for diversions are not explicitly metioned in the data. 

* Note: Any delay less than 15 minutes is not considered as delay for this analysist.

### Drill through page provides much deeper insights into each airline's performance and digs deep into the reasons for delays and cancellations.