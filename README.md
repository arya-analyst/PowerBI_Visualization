# Power BI : Hospitality Sector Dashboard

Explore this GitHub repository where I leverage the power of Power BI to create a snowflake schema for a hotel-chain dataset and conduct statistical analysis for key insights.

![Dashboard](https://github.com/arya-analyst/PowerBI_Visualization/blob/main/BI_Dashboard.png)


## Objective:

The project aims to analyze extensive sales data to uncover valuable insights that can drive business decisions.

The primary objectives include identifying and calculationg key metrices such as ***total revenue***, ***Occupancy %***, ***Average Daily Rate***, ***Revenue Per Available Room***, ***Realisation %***, and creating compelling visualizations to effectively communicate the findings.

This project demonstrates proficiency in handling and analyzing large datasets, ultimately providing data-driven recommendations to optimize strategies to fuel business growth.

## Key Metrices:

- **Revenue**: Total revenue realized during a said period
- **RevPAR**: RevPAR or Revenue Per Available Room represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotels measure their revenue generating performance to accurately price rooms.
- **DSRN**: DSRN i.e., Daily Sellable Room Night tells on average how many rooms are ready to sell for a day considering a time period
- **Occupancy** %: Occupancy means total successful bookings happened to the total rooms available.
- **ADR**: It is the ratio of revenue to the total rooms booked/sold. 
- **Realisation** %: It is nothing but the succesful "checked out" percentage over all bookings happened.

## Data Analysis and Visualization Workflow:

- **Data Ingestion**: Imported the dataset, formatted as CSV files, contained in a folder, into Power BI Desktop to initiate the analysis process.
- **Data Profiling**: Navigated to the Power Query Editor and opted to profile the entire dataset for a more exhaustive understanding of its characteristics.
- **Data Customisation**: Based on the feedback from stakeholder, we considered Friday and Saturday as weekend and from Sunday to Thurdsay as weekdays. In PowerBI, Sunday weekday number is 1, Monday is 2 and so on. So, if weekday number is greater than 5, then weekend or else weekday.
- **Data Modelling**: Establishing relationship between different data tables.
 ![Reationship](https://github.com/arya-analyst/PowerBI_Visualization/blob/main/Relationship.png)
- **Interactive Filters**: Enhanced user engagement and exploration capabilities by integrating visual filters for key categorical fields such as "Location, "Room Class", "Months", "Week" and "Hotels"


## Recommendations:

- From the below chart, we can derive that the Average Daily Rate is nearly a flat line. We can introduce dynamic pricing depending upon the day of the week, occupancy percentage, ‘season’ to attract more revenue. We can decrease the price on weekdays to attract more customers and similary we can also revise our pricing depending on the climatic seasons. Summers, in India, are generally a holdiday season - we can introduce new packages to attract more customers during this time.

![Trend By Key Metrics](https://github.com/arya-analyst/PowerBI_Visualization/blob/main/Trends%20by%20Key%20Metrics.png)

- We can see that the ***occupation rate*** has a direct correlation with the ***average rating*** that they have received. We need to dive deep to analyze the root cause behind the low ratings of certain hotels. It can be due to many reasons including cleanliness, aesthetics, facilities provided including food, easiness in check-in and check-out, staff behavior etc.

![Info Table](https://github.com/arya-analyst/PowerBI_Visualization/blob/main/InfoTable.png)

- We can see that the ***realization rate*** is more or less similar for all the channels and there’s not much of a difference in their ADR as well. We can decrease the ADR for direct online channel – as the other online channel charge a certain commission - to get more bookings, hence resulting in more revenue.

![Realisation & ADR](https://github.com/arya-analyst/PowerBI_Visualization/blob/main/Realisation%26ADR.png)

- The cancellation rates are >20% for all the hotels. That’s 1 of every 5 bookings we get! The rate remains the same irrespective of the day of the week or room type. We can introduce measures like having a debit/credit card deposit policy or offering discounts on prepaid bookings.
