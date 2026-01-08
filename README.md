<img width="93" height="21" alt="image" src="https://github.com/user-attachments/assets/f8577da2-1d0e-440a-895f-486113c17fe7" /># Video Game Sales Analysis

## Project Overview
This project analyzes historical video game sales data to identify market trends, regional preferences, and key performance drivers across the global gaming industry.
The analysis was conducted using SQL for data preparation and exploration, and Excel for visualization and dashboard creation.

This project simulates a real-world data analyst workflow, from raw data cleaning to insight generation for business decision-making.

## Dataset
- Source: Kaggle – Video Game Sales
- Description: Sales data of video games across multiple regions (North America, Europe, Japan, and Global), including information on genre, platform, publisher, and release year.

## Tools & Technologies
- SQL (MySQL):
    - data cleaning and transformation
    - Exploratory Data Analysis (EDA)
    - CTEs and window functions
- Excel: 
    - Data cleaning and validation
    - Pivot tables
    - Interactive dashboard with slicers and charts

## Workflow 

SQL
The following steps were performed using SQL:
- Created staging tables to preserve raw data integrity
- Removed duplicate records
- Standardized categorical values (genre, publisher, platform)
- Identified and handled null or blank values
- Used CTEs to structure EDA queries
- Applied window functions (RANK() / ROW_NUMBER()) to identify top-performing games, genres, and platforms

Excel
In Excel, the dataset was further prepared by:
- Cleaning and validating remaining inconsistencies
- Ensuring numeric and categorical data accuracy
- Preparing the data for pivot-based analysis and visualization

## Exploratory Data Analysis (EDA)
The analysis focused on answering key business questions, such as:
- Which regions contribute the most to global video game sales?
- What genres and platforms dominate each regional market?
- Which publishers consistently generate the highest sales?
- How has global video game sales changed over time?

## Key Insights
Golden Era of the industry
- Global video game sales peaked in 2009.
- Rapid growth occurred between 200 and 2009, driven by popular consoles such as the Wii, PlayStation 2, and Nintendo DS.

Top Publishers
- Electronic Arts (EA) leads the market, nearly double the sales of Electronic Arts (EA).
- Other major contributors include Activision, Namco Bandai Games, and Ubisoft.

Most Popular Genres
- Action is the top-performing genre globally.
- Followed by Sports and Misc.

Best-Selling Platforms
- Nintendo DS is the highest-selling platform in the dataset .
- Wii and PlayStation 3 show closely matched performance.

Top-Selling Games
- Wii Sports is the best-selling game of all time, largely due to console bundling.
- Classic titles such as Grand Theft Auto: San Andreas and Pokémon Red/Blue remain among the top sellers globally.

## Dashboard & Visualization
An interactive Excel dashboard was created to support exploratory analysis:
- Pivot tables summarizing sales by region, genre, platform, and publisher
- Charts highlighting trends and comparisons
- Slicers enabling users to filter insights dynamically by year, region, and genre

## Business Relevance
- Publishers can tailor game genres based on regional market preferences.
- Marketing strategies can prioritize regions and platforms with higher sales potential.
- Sales trends highlight the industry’s transition period following the peak of physical game sales after 2010.


## Conclusion
This project demonstrates an end-to-end data analysis process using SQL and Excel, emphasizing data cleaning, structured analysis with CTEs and window functions, and insight-driven visualization.
It reflects the core skills required for an entry-level data analyst role.

## Author
Alexander Ludwig
Aspiring Data Analyst
Skills: SQL | Excel | Data Cleaning | EDA | Dashboarding
