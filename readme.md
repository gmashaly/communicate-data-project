# Ford GoBike System Data Exploration
## by (Gamal Mashali)


## Dataset
This project analyzes the data collected about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This dataset consists of data about all monthes of 2018 and some monthes of 2019 .it is avalibale on this link : https://s3.amazonaws.com/fordgobike-data/index.html

The dataset includes:

an ID number for each bicycle
how long it was rented for, in seconds
the beginning and end staton ID, latitude, longitude and station name
the start and end time
the year the user was born
the gender of the user
whether the user has a subscription to the service or not There are 2583000 rows and 19 columns.
There was some cleaning needed to the dataset. This included:

- Drop the rows which contains null values in columns.
- Deleting the rows without gender or birth year
- Change data types, for start_time and end_time.
- Extract months and days of the week from start_time.
- Create column for user's age on 2018

## Summary of Findings

First, I discovered that 88% if the user type is subcriber, and only 12% are customers.

The majority of the riders are male, at 74%. 25% are female and 2% identify as other.

The mean age is 35.4 years old.

This analysis is quite illuminating as it shows that subscribers predominately use the ride service on Monday through Friday, while customers ride the most on the weekends. This is most likely due to subscribers using the service to commute to work, while customers use the bikes on an occasional basis for something unusual in their schedule.

Both customers and subscribers have a similar trend to their monthly usage, where it increases throughout the winter and spring until it drops in May, and for the remainder of the winter. However, the most popular usage month for customers is April, while the most popular month for subscribers is March.

While there is less female and other gender usage than male, the trend between customers and subscribers of each gender is similar. Customers of all genders use the service more often on the weekends, while subscribers use the system during the week, predominately.

## Key Insights for Presentation

For my presentation, I focused on the difference in usage for customers and subscribers. then, I showed how gender also comes into play. I showed the univariate results first, such as usage on days of the week, and usage over months. I then continue to see how adding more variables influences the results. My conclusion is that whether a user is a customer or a subscriber has the biggest influence on results, compared to gender.