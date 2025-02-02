# Power BI : Hospitality Sector Dashboard

Explore this GitHub repository where I leverage the power of Power BI to create a snowflake schema for a hotel-chain dataset and conduct statistical analysis for key insights.

![Dashboard](https://github.com/arya-analyst/PowerBI_Visualization/blob/main/BI_Dashboard.png)

## Objective:

The project aims to analyze extensive sales data to uncover valuable insights that can drive business decisions.

The primary objectives include identifying *Occupancy %*, *Average Daily Rate*, *Revenue Per Available Room*, *Realisation %*, calculating key revenue metrics such as total revenue, and creating compelling visualizations to effectively communicate the findings.

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
  ![Reationship] (https://github.com/arya-analyst/PowerBI_Visualization/blob/main/Relationship.png)
- **Interactive Filters**: Enhanced user engagement and exploration capabilities by integrating visual filters for key categorical fields such as "Location, "Room Class", "Mpnths", "Week" and "Hotels"

## Recommendations:


