# TTC-Bus-Delay-Analysis

Transportation has been a tenant of a stable city life for centuries. One of the most important and vast aspects of transportation in any city is the constant usage of buses.
 
Naturally, with these extensive systems in place, working concurrently with other city systems, there are bound to be hiccups and incidents that impede the flow of the bus transportation system. We want to explore if there are any abnormal pressure points that are beyond pre and post-work hours on weekdays.
 
In this analysis, we will go through the first six months of the Toronto Transit Commission's bus usage and the delays involved to understand how and where these delays have taken place in the year 2022.

|**Parts**|**Description**|**Queries Used**|
| :------------- |:-------------| :-----|
| Part 1      |Categorizing and Cleaning Variables. I clean up irrelevant data and categorize variables that will be used in future parts. |(Queries used: Delete, Count, Distinct, Group by, Order by, Where, Case/When Statements,)|
| Part 2     |   I begin analytical work to count incidents and place them in above mentioned variables and in various modes of time.   | (Queries used: Count, Distinct, Group By, Order By, Distinct, Case/When Statements) |
| Part 3 |    I begin finding pressure points in the entire bus system where alarming rates of incidents occur. | (Queries used: Count, Distinct, Group By, Sum, Over, Order By, Case/When Statements)  |
| Part 4 |    I confirm above found pressure points and see if they reveal other causes of concern in the bus system.     |Queries used: Count, Average, Distinct, Group By, Order By, Where)  |

In brief conclusion, we can see that there are several incidents(Mechanical, Operations and Diversion) and several months(January and June) that are abnormal pressure points in the system. There are also several locations that have an irregular amount of delay incident counts that should be looked at to improve traffic flow citywide.

This dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/reihanenamdari/toronto-bus-delay-2022) which, in turn, was taken from the [Open Data source](https://open.toronto.ca/dataset/ttc-bus-delay-data/) provided by Toronto.Ca

Corresponding Tableau Visualizations will be attached to the repo.
