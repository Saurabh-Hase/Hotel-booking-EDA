# Hotel-booking-EDA
In this project, we are provided a hotel booking dataset to explore and analyze the data to discover important factors that govern the bookings. The EDA has been performed on the given data set (containing 119390 rows and 32 columns) to understand about their customer base and find out the trends which could prove beneficial to the hotel industry.

As the first step, features of data and its attributes were explored using Descriptive statistics and the data types for all the variables and the features containing null values have been identified.

Further, Data cleaning have been performed in which the null values of the categorical variable (country) was filled with the mode while the null values of numerical variables were filled with their respective means. Further, the rows with zero number of guests were dropped as such data is of no use. In last step of pre-processing, the variables with ‘string’ data type were changed to ‘int’ type.

Then, EDA was performed using Data visualization libraries including seaborn and matplotlib. To better understand the dataset, various points were analyzed such as which type of the hotels were mostly booked, their price distribution over the year, the months and meal preferred by the guests, types of the guests, the number of guests who are repeating their bookings and many more.  

From the above analysis it can be concluded that- 
Mostly, people have booked city hotels as compared to resort hotels which could due to higher accommodation cost of resort hotels. 
Around 37 % of the time the guests have canceled their bookings which is quite a lot. The majority of the cancellation were made in City hotel which is 41.73 % while booking cancellation percentage in Resort hotel is 27.76 %. 
Highest number of bookings have been made during the season of summer end and autumn beginning. Thus, the prices of resort hotels are much higher during this season.
With the ease of booking directly from the website, most people tend to skip the middleman to ensure quick response from their booking and save extra money.
Most of the guests stayed at the hotel for 2 nights which were found to be weekday's night.
Majority of bookings is for couple type accommodation, followed by single type accommodation and least for family/friends’ type.
Number of repeated guests were low which seems to be a concern. The guests who are coming to the hotel again are not canceling their bookings frequently. It is found that 87% of the guests got their preferred room.
