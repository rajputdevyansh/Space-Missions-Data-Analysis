# Space Missions Analysis : 1957 - 2022


## View the project

[Live Preview](https://www.devyanshrajput.live/Space_Missions_Dashboard.html)
## Screenshots

### Space Missions Analysis Dashboard

![App Screenshot](https://github.com/rajputdevyansh/Space-Missions-Data-Analysis/blob/main/Space%20Missions%20Analysis/Demos/Dashboard.png?raw=true )


## 🛠 Skills

### Excel, PowerBI, PowerQuery

## Documentation

### Problem Statement

- All space missions from 1957 to August 2022, including details on the location, date, and result of the launch, the company responsible, and the name, price, and status of the rocket used for the mission.
- How have rocket launches trended across time? Has mission success rate increased?
- Which countries have had the most successful space missions? Has it always been that way?
- Which rocket has been used for the most space missions? Is it still active?
- Are there any patterns you can notice with the launch locations?

### Dataset

- Source: Next Spaceflight
- License: Public Domain
- Downloaded from https://www.mavenanalytics.io/data-playground

### Results: Insights

- The success rate of space missions has improved over the years, with 4162 Missions succeeded out of 4630 Total Missions with a 90% success rate, after a period of decline in the 1960 - 1970 due to technological advancements and better safety measures.
- The USA, Russia, China, Japan, and India are the top five countries in the number of space missions, with the USA & Russia leading by a large margin. The USA has the most successful missions with 1299 out of 1469 missions & followed by Russia with 1358 out of 1455 missions.
- SpaceX, NASA, ISRO, CNSA, and Roscosmos are the top five organizations in terms of the number of space missions, with SpaceX being the most active and innovative in recent years.
- Maximum no of missions were done by RVSN USSR with a Total of 1777 missions & followed by CASC with a Total of 338 missions. With 446 missions Cosmos-3M(11K65M) retired rocket was used for most space mission.

### Data Validation Using Excel

- Ensure that all records have valid dates, and that the date range is within the specified bounds (1957 to January 2022).
- Check that location data is consistent and can be mapped to a known list of launch locations.
- Validate that the organization, rocket name, price, and status fields are populated and fall within expected values.

### Data Cleaning and Trsanformation using PowerQuery & Excel

- Handle inconsistent data in the dataset. This involves standardizing entries.
- Standardized the price column by multipliying the price column to converted USD million to USD.
- Created a new table for date based on mininium and maximum date from the date coloumn.
- Created a country coloumn using the the text to coloumn feature in excel to extract the country name from the location coloumn.

### Data Analysis Using PowerBI

- Total number of missions: The total count of space missions conducted over a certain period.
- Involved organizations: The organizations that have participated in these space missions.
- Participating countries: The countries that have been involved in these space missions.
- Types of rockets used: The different types of rockets that have been used in these missions.
- Launch locations: The locations from which these space missions have been launched.
- Associated costs: The costs associated with these space missions.

### Data Visualization using Power BI

- Performed data visualization using Power BI to create interactive and insightful reports and dashboards.
- Created DAX measures to define custom calculations and metrics for the data.
- Created various line, Donut, and column charts to visualize the data and compare different categories and trends.
- Created contextual and categorical filters and slicers to allow users to filter the data and gain insights.

## Feedback

If you have any feedback, please reach out to us at rajputdevyansh9@gmail.com or https://www.devyanshrajput.live
