# Citi-Bike-Analytics---Tableau

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)
Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.** 

**Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.** 



Visualizations
----------------------------------------------------------------


Citi Bike Program Analysis
After creating and analyzing our visualizations, there were many phenomena to be uncovered.

1	* Today, what are the Top 10 stations in the city for starting a journey? (Based on data, why?)
	* Today, what are the Top 10 stations in the city for ending a journey (Based on data, why?)

The first phenomenon i want to point out is that the trips for the most used bikes are often started and ended on or around the same stations, 
this may indicate that we need to increase our supply of bicycles in these areas. Adding more bikes to these 
stations will allow more users to have a bike available as well as preventing the same bikes from enduring 
heavy usage which will increase our repair fees, or worse, the risk of user injury.

2. 	* How many trips have been recorded total during the chosen period?
	* What are the peak hours in which bikes are used during summer months?
	* What are the peak hours in which bikes are used during winter months?
The second phenomenon that I want to recognize is that the most trips were taken in month of October and the peak time shows 6:00pm.
The bump around 6 PM could also be from students leaving class for the day. In summer months, the peak time shows 6:00pm, and winter
months, the peak time shows 5:00pm to 6:00pm. This makes sense as above observation for the peak time. 

3. How do demographics affect trip duration?
	- How does trip duration change between factors such as:
		-age?
		-gender?
		-subscriber vs. one-time customer?
The third phenomenon that i would like to recognize is that data shows more female and male subscribers than one time customers.
Also male seems to take more trips compare to female. Again for some reason month of October shows most trips taken by male.
It seems most of our rides are between ages of 25 to 41 which has taken the most trips. However, However, there are some red flags raised as it appears that we noticed 
not confirm age in any way and that the user can say they were born in any year. This was noticed when we had 
multiple users over 100 years old riding bikes. This is extremely unlikely and caused that data to be filtered. 
It may be wise to start having users validate their age so we do not have invalid data or even have underage children 
lying about their age to ride our bikes.
