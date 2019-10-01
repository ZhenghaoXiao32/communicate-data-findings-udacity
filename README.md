# Analyzing Ford GoBike Data

## Dataset
Ford GoBike is a regional public bicycle sharing system located in San Francisco Bay Area, California. In this project, history data of the whole 2018 year was used. By investigating the Ford GoBike dataset, I intent to give some insights in business area which can help the company increase its revenue. Several visualizations are picked to illustrate the findings I evaluated from data investigation. The cleaned dataset has 1743806 rows and 22 columns, including ID, name, latitude, longitude of start and end station, start time and data, end time and date, bike ID, user type, member year of birth and member gender. In addition to the original 16 columns, I added 6 new columns derived from feature engineering: member_age, start_time_month, start_time_month_num, start_time_weekday, start_time_hour, duration_min.

## Findings
The findings in bivariate exploratory part are proven to be right in multivariate exploratory part. In the heat map, I found that is a good example of how multi-dimensional visualization can carry more information if appropriate encoding was used. According to these plot, there is a different trend between subscribers and customers that the most popular time periods for customer to ride Ford GoBike are 5 pm in weekdays and 11 am to 5 pm in weekends while subscriber's is rush hours in weekdays. Based on that, I think there are bunch of promotional actions can be applied to increase the revenue get from customers.

