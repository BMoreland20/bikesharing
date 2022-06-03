Overview of the analysis:

For this week’s challenge we are tasked with performing a minor ETL on the CitiBikes data csv to update the tripduration column to a datetime format instead of an integer.

After this was completed, we were tasked with building the visuals of the data for the “Checkout Times for Users”, “Checkout Times by Gender”, “Trips by Weekday for Each Hour”, “Trips by Gender (Weekday per Hour)”, and “User Trips by Gender by Weekday”

See below link to the tablau dashboard:

[link to dashboard](https://public.tableau.com/views/Week_14_Challenge_16542224310100/CheckoutTimesforUsers?:language=en-US&:display_count=n&:origin=viz_share_link)


Results:

For our first visual we created the checkout times per minute by users.  As we can see in the image below the bikes are primarily used within the first hour and under 20 minutes.  It could be assumed that the bikes are typically being used for short trips to get to nearby places.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/1%20Checkout%20Times%20for%20Users.PNG)

For our second visual we created the checkout times per minute but broken down by gender.  In this visual we see a similar graph as to the first that the highest number of bike rentals last under 20 minutes.  However, in this instance we can see that males are the largest number of users to use the bikes with females in second and unknown in third.  This can be seen in the image below.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/2%20Checkout%20Times%20by%20Gender.PNG)

For our third visualization we created a heat map of the times bikes were checked out.  This showed the hours that the bikes were used the most.  We can see in the below image that from between 17:00 and 19:00 the bikes are used the most during the week.  With an almost even spread from 08:00 to 19:00 pm the weekends.

During the week it could be hypothesized that people are using the bikes to get to work as bike usage picks up between 06:00 and 09:00 in the morning and again between 17:00 and 19:00 this would coincide with an 8-hour work day.

As for the weekends it could be hypothesized that people are using the bikes for leisure travel about the city to get to various locations.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/3%20Trips%20by%20Weekday%20per%20Hour.PNG)

In the fourth visualization below we took the heat map from above but broke down the data by gender.  As mentioned above we see the same pattern of usage but can now see that men are still the primary users of the bikes.  This can be corroborated by the results we saw in visualization 2.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/4%20Trips%20by%20Gender%20(Weekday%20per%20Hour).PNG)

In the final visualization we combined the previous visualizations into one.  In this new visualization we can now see the usertype, gender, and the heatmap of usage during the weekdays.  In the below image we can see that our previous results still hold true that men primarily are using the bikes.  But we now can see that subscribers are the ones who are primarily using the bikes with non-subscribers not using the bikes as much.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/5%20User%20Trips%20by%20Gender%20by%20Weekday.PNG)

Summary:

As we can see from our results our bikes are primarily used for short rides lasting less than 20 minutes.  Of this our primary customers are male subscribers renting our bikes.

We can see that the best times to perform maintenance on our bikes is between 23:00 and 04:00 on most days of the week.

One visual we can add to our list is a map looking at the breakdown of high use areas.  This could help with better placement of our bikes to increase profits.  See image.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/Map.png)

Our last additional visual we can add it overall bike usage.  This can help prioritize what bikes we work on to maintain to keep them up and in working order.  This can not only help earn us more money but save us money in potential legal fees.  See the image below for justification.

![This is an image](https://github.com/BMoreland20/bikesharing/blob/main/Resources/Bike%20Utilization.png)
