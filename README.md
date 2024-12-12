# Google Playstore Analysis
## Objective
The objective of this project is to forecast the number of app installs based on app information and user reviews. The aim is to provide valuable insights to app developers and potential investors in identifying the next breakthrough app. By analyzing beta focus groups, user feedback, and app reviews, this project predicts an app's success and empowers stakeholders to anticipate potential profits. It also highlights the significant influence of reviews on an app's performance in the market.

## Dataset
The dataset used for this project provides a comprehensive view of app-related information, with 10,841 records across 13 columns:

| **Column**         | **Description**                        |  
|---------------------|----------------------------------------|  
| App                | Name of the app                       |  
| Category           | App category                          |  
| Rating             | Average user rating                   |  
| Reviews            | Total number of user reviews          |  
| Size               | Size of the app                       |  
| Installs           | Total installs                        |  
| Type               | Free or Paid                          |  
| Price              | Price of the app (if paid)            |  
| Content Rating     | Age group for the app                 |  
| Genres             | Genres of the app                     |  
| Last Updated       | Date of last update                   |  
| Current Ver        | Current version                       |  
| Android Ver        | Minimum Android version required      |  


## Key Statistics
Total Apps: 9,349
Total Installs: 128 billion
Total Revenue: $352 million
App Categories: 33
Genres: 118
## Technologies/Tools
Data Analysis and Cleaning: Python (Pandas, Matplotlib, Seaborn)
Data Storage and Retrieval: SQL
Dashboarding: Power BI
Data Exploration: Excel
## Process
### Data Exploration (EDA)

Examined dataset structure, column distributions, and detected outliers.
### Data Cleaning (Python)

Handled missing values in the Rating column.
Converted data types for columns like Reviews, Installs, and Price.
Removed duplicate records for consistency.
### Database Management (SQL)

Stored cleaned data in SQL for efficient querying and retrieval.
### Visualization and Insights (Power BI)

Created an interactive dashboard to showcase key trends and insights.
Challenges
Addressing inconsistencies in the dataset, such as outliers and missing values.
Analyzing data with numerous unique values across multiple columns.
## Results
Key Insights
Top Categories by Installs:
Games: 28 billion
Communication: 17 billion
Tools: 11 billion
App Distribution by Content Rating:
Most apps are rated for "Everyone" while the least are "Unrated".
Top Apps by Installs:
Google Photos, Hangouts, Subway Surfers (Top 3)
App Type Distribution:
Free Apps: 92.67%
Paid Apps: 7.33%
Revenue Insights:
Total Revenue: $352 million
## Visualizations
Category-wise Total Installs
Percentage of Free vs Paid Apps
Sum of Reviews by Category
Count of Apps by Content Rating
Top Apps by Installs
Count of Apps by Category
## Conclusion
This project provides significant insights into the app market on the Google Playstore, enabling new businesses to make informed decisions about app development. The dashboard offers a clear view of market trends, helping developers and investors understand customer preferences and app success factors.
