# Ford-GoBike-Data-Analysis
Final Project for the Data Analysis Nanodegree on Udacity.

Ford GoBike Dataset Exploration
By Sarah Abdelbar
 
 
1.	Dataset
For this project, I chose the dataset from Ford GoBike website. The data had entries for all of 2018 bike trips. The data initially included 16 columns and 2,023,431 rows. The following steps were taken to prepare the data for the Exploratory analysis.
 
•	A copy of the dataset was created to apply the necessary modifications \newline
•	ID column was converted to object instead of float
•	Start and end time columns were converted to timestamp
•	New Columns were created for the month, day and hour, as well as for the members age
•	Throughout the analysis phase, extra steps were taken like classifying members in age groups, and calculating contribution to total trips (as a %)
This is how the clean copy of the dataset looked like at the end. 
 
 
2.	Summary of Findings
From the analysis, the following conclusions could be drawn
•	Most of the users (88%) are customers, and only 12% are subscribers
•	More than 40% of the users are between 30 and 40 years old, and 30% are between 20 to 30 years old
•	Throughout the year, most of the bike trips happen in summer, mostly around July. This trend is consistent with most of the age groups as well, with the spike in July is more significant in 30-40 and 20-30 age groups compared to other age groups
•	Subscribers would usually spend 10 minutes on the bikes, mostly using them in weekdays, while customers spend more than 25 minutes and most of the trips happen in weekends. Subscribers also use their bikes between 7am-9am and again between 5pm to 7pm, while customers either use the bikes during the day on weekends of after working hours on weekdays. This brings us to the conclusion that users subscribe to this service to they use it as a way to commute to their work every day, while customers (88%) from 2018 users, use this bike system for Leisure.

 
3.	Key Insights for Presentation
All the visuals used to interpret the data and reach the conclusions in section two of this report are presented in the slide deck. Univariate, Bivariate and Multivariate plots are presented so the findings are communicated in a way that is easy for the reader to observe and reach their own conclusions. 
Here is a summary of visuals included in the slide deck.
•	Univariate exploration
o	Exploring monthly trends of number of trips completed
o	A pie chart showing the user split (% of customers and subscribers)
o	Age Group contribution to total trips completed (%)
o	A line chart representing the monthly trends of each age groups
•	Bivariate exploration
o	A comparison of the average trip duration for each user type
o	Number of trips for each user type throughout the different days of the week
o	The hourly trends of each user type
•	Multivariate exploration
o	The split of each user type by Gender and number of trips
o	The split of each user type by Gender and the monthly trends throughout 2018


