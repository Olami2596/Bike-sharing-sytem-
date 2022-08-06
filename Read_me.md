# Ford GoBike System Data Exploration 
## By Tijani Abdul-hakeem

### Ford GoBike System
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
I created a distance column from the start_station_latitude, end_station_latitude, start_station_longitude, end_station_longitude columns and dropped them afterwards. The start_station_id and end_station_id columns were filled with 0 in place of Nan and the member_birth_year column was filled with the mean of the column in place of the Nan values. The start_station_id, end_station_id  and member_birth_year were changed from float to int. Dropping the start_time and end_time columns as they are not needed for the analysis. Getting the age of the users from the member_birth_year column.

## Summary of Findings
During the exploration of the dataset it was discovered that the bike sharing system was popular among people in their late twenties and thirties and the age was determined by subtracting the birth year of users from the current year (2022). A count of each gender also revealed that there are more male users than female users. I verified the relationship between age and time spent, age and distance travelled using a scatterplot and discovered there was no relationship between them. 

## Key Insights for Presentation
For the presentation I focused on the location where the bike system were very popular and least popular by finding out the top most and least visited start stations and they were displayed on a horizontal bar chart. This was done as to gain insights into locations where intense advertisement can be targeted towards in order to gain more users.

After that a countplot was made in order to determine the amount of subscribers compared to customers and I discovered the number of subscribers greatly exceeds the number of customers.

In order to determine which gender an advertisement can be targeted towards to gain more users a countplot was made and I t was discovered that the male users greatly exceeds the amount of female users. 

Initial exploratory analysis reveals that alot of users were in their thirties and in order to determine if the age of the users affected the time spent and distance travelled, two different scatterplots were created and it was determined that the age of the users had no effect on the distance travelled and time spent.