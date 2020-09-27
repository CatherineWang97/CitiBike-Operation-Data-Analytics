# CitiBike-Operation-Data-Analytics


### Background Information and Operation Problem to Solve:

As the first and biggest bike share program in NYC, Citi Bike has almost 800 stations and 13000 bikes as of September 2019 (“Citi Bike”). However, the number of 13000, is far from meeting the demand and customers’ needs because of the rebalancing problem. The Wall Street Journal analyzed that the Citi Bike system struggles to match the bike supply and demand; customers’ complaints about Citi Bike are majorly around the rebalancing problem (Tangel).

Indeed, customers are frustrated to find that they fail to find bikes or docks at some stations while plenty of bikes and docks are available at others that are several blocks away from them. The problem of rebalancing not only greatly affects customer satisfaction in a negative way, but also causes a large waste of bike and dock resources. To save Citi Bike from declining reputation and to save Citi bikes from unnecessary resource waste, it is of great need to enact effective strategies and take decisive actions promptly.


### Approach 1: Descriptive and Diagnostic Data Analytics

By closely monitoring the real-time bike system on weekdays where the rebalancing problem occurs, we find that the residential zones have the most bikes in the evening and the commercial zones have the most bikes in the morning on weekdays, which causes the rebalancing dilemma. We plan to regulate the real-time bike data for three days each month to get descriptive data to understand the rebalancing dilemma analytically.

Meanwhile, diving deeper into the data by visualizing historical data on Tableau will give us accurate metrics such as the most / least used stations in different time periods, the most popular routines of users, and the effect of various seasons and weather on customers’ use of Citi bikes. The historical data of users will be gained and extracted from the system data section on the Citi Bike website; the seasons and weather data will be obtained from Weather Facts New York City.com.


### Approach 2: Prescriptive Analytics

The solution is composed of two parts -- the default setup of stations and docks, and bonus initiative for customers. First of all, applying data analytics and visualization to analyze historical data helps us to determine the number of docks in each station and the location of stations in New York City. The number of docks needed in each station could be calculated depending on the different time, location, weather, events, and alternative transportation of which data could be collected from the NYC department of transportation website, the City of New York's bicycle data, the system data from Citi Bike website and Weather Facts New York City.com.

The second part of the solution is to offer customer bonuses and build a customer-led solution to the rebalancing problem. By analyzing the density of routes and patterns at different times and seasons in NYC, for the most popular routes at a specific time and season, customers who follow the opposite routes could gain a bonus from Citi Bike. This mechanism of customer encouragement could automatically offset the rebalancing problem.

<img height = "230" width = "700" src=https://github.com/CatherineWang97/CitiBike-Operation-Data-Analytics/blob/master/CitiBike_1.png /> 
<img height = "300" width = "700" src=https://github.com/CatherineWang97/CitiBike-Operation-Data-Analytics/blob/master/CitiBike_3.png />
<img height = "470" width = "1100" src=https://github.com/CatherineWang97/CitiBike-Operation-Data-Analytics/blob/master/CitiBike_4.png />
<img height = "470" width = "1100" src=https://github.com/CatherineWang97/CitiBike-Operation-Data-Analytics/blob/master/CitiBike_5.png />

#### References:

Tangel, Andrew, and Austen Hufford. “In New York, It's a Crush to Find a Citi Bike During Rush.”The Wall Street Journal, Dow Jones & Company, 16 Sept. 2016, https://www.wsj.com/articles/in-new-york-city-its-a-crush-to-find-a-citi-bike-during-rush- 1473988014.

Motivate International, Inc. “Citi Bike: NYC's Official Bike Sharing System.” Citi Bike NYC, https://www.citibikenyc.com/.
