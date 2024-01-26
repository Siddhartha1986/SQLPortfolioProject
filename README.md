

# COVID-19 Data Analysis SQL Project

## Project Overview
This SQL project is focused on analyzing COVID-19 data to uncover insights related to cases, deaths, and vaccination rates across different countries and continents. The project uses data from two main tables: `CovidDeaths` and `CovidVaccinations`, contained in the `PortfolioProject` database. Credits goes to **Alex the Data Analyst, YouTube channel for organizing the data analysis bootcamp**

## Data Source
The data used in this project is sourced from a comprehensive COVID-19 dataset, which includes information on cases, deaths, and vaccinations. This data is continually updated to reflect the most current figures.

## Objectives
The primary objectives of this project are to:
- Analyze COVID-19 morbidity and mortality rates by country and continent.
- Investigate the relationship between COVID-19 cases and population demographics.
- Understand vaccination rollout progress in different regions.

## Queries
The project includes several SQL queries, each designed to answer specific research questions:

1. **Basic Data Retrieval:** Select basic COVID-19 data, filtering out records where the continent is null.

2. **Mortality Rate Analysis:** Calculate the mortality rate (percentage of deaths among total cases) for specific locations, like Nepal.

3. **Morbidity Rate Analysis:** Assess the morbidity rate (percentage of population that contracted COVID-19).

4. **Infection Rate by Country:** Identify countries with the highest rate of infection relative to their population.

5. **Highest Death Count by Country:** Determine countries with the highest COVID-19 death counts.

6. **Continental Analysis:** Compare death counts and mortality rates across different continents.

7. **Global Trends:** Analyze global COVID-19 trends, including daily death percentages.

8. **Vaccination Analysis:** Evaluate vaccination progress in relation to total population, using both direct queries and Common Table Expressions (CTEs).

9. **Data Aggregation for Visualization:** Create a view to facilitate data visualization, focusing on the percentage of the population vaccinated in various locations.

## Tools and Technologies
- SQL Server: For database management and query execution.
- Data Visualization Tools (e.g., Tableau, Power BI): To visualize the data from the created view for more accessible interpretation.

## How to Use
- Ensure SQL Server (or a compatible SQL database system) is installed and running.
- Import the `PortfolioProject` database into your SQL Server instance.
- Execute the provided SQL queries to analyze the data.
- For visual analysis, link the SQL database to a data visualization tool and use the created view for building dashboards or reports.

## Future Scope
- Update the dataset periodically to include recent data.
- Expand the analysis to include more granular demographic data.
- Perform time-series analysis to observe trends over the duration of the pandemic.



