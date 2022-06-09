# Citibike Data

As the new lead analyst for the New York Citi Bike Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.
Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.
However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Results

<img width="760" alt="image" src="https://user-images.githubusercontent.com/95598645/172769289-8f83affb-0909-4ca2-bd76-36dc9183fc50.png">
- Initial analysis focused on looking at the least popular start and end stations. This was intended to find a correlation between the two. If a station showed up as unpopular for both start/end, that would make a case for removing the station. Fortunately, no match was found, so seems like all the current stations play an important enough role to stay around!

<img width="836" alt="image" src="https://user-images.githubusercontent.com/95598645/172769857-4f775082-408b-4d73-9a00-f9152b25efee.png">
- Next analysis was looking at usertype. The percentage of subscribers turned out to be much much larger than the customers that do not have a subscription. To check if subscribers were using their subscription to maximum capacity, I compared trip duration for the different types of users. Trip duration was significantly higher for subscribers, so clearly they are making good use of their subscription!

<img width="884" alt="image" src="https://user-images.githubusercontent.com/95598645/172769801-6a3410e7-a7c1-4197-b895-b8a9febd0fec.png">
- Finally, I looked to see if there was any significance between user type and location of the start/end stations. Indeed, I did find a correlation. There were certain stations where only one of the two user type would start / end. An intriguing example is the one station where only subscribers tend to end. This must be in an area with fewer tourists or things to do, as maybe only those who need to go home end their trips there. 

## Further Considerations
- This is just a preliminary analysis and so it is difficult to draw conclusions. Many more dashboards can be built using this data, and a yearly analysis would be great to see if there are any trends in the data. If given more time, specifically for the categories I was focusing on, I'd say it would be interesting to see if there is a correlation between the stations that only 1 user type uses and the popularity of that station. 

Link to Tableau Public: https://public.tableau.com/app/profile/elza.hayyat/viz/TableauHomework-CitiBikeAnalytics_16527634807500/Story1?publish=yes
