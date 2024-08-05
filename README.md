

# COVID-19 Data Exploration

## Project Overview
This project explores COVID-19 data using SQL, demonstrating my various  SQL skills and techniques to analyze the pandemic's impact across different countries and continents.

## Data Sources
The analysis uses a 2022 COVID-19 dataset which was divided into two main tables:
- CovidDeaths
- CovidVaccinations

## Skills Demonstrated
- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Converting Data Types

## Queries and Analysis
1. Initial data selection from CovidDeaths table
2. Calculation of death percentage in specific countries (e.g., South Africa)
3. Analysis of total cases vs population to show infection rates
4. Identification of countries with the highest infection rates
5. Countries with the highest death count per population
6. Analysis by continent, showing highest death counts
7. Global COVID-19 numbers over time
8. Comparison of total population vs vaccinations
9. Use of CTE to perform calculation on partition by
10. Use of Temp Table to perform calculation on partition by
11. Creation of View for later visualizations

## How to Use
1. Ensure you have access to a SQL database with the CovidDeaths and CovidVaccinations tables.
2. Run the queries in order as they appear in the script.
3. Modify country names in the 'like' clauses to focus on specific regions of interest.

## View Creation
The final query creates a view named 'PercentagePeopleVaccinated' which can be used for future analysis or visualization projects.

## Notes
- Some queries are commented out and can be uncommented for specific analyses.
- Ensure proper data types and table structures match your database setup.

## Future Work
This script provides a foundation for further COVID-19 data analysis. Possible extensions include:
- Creating more complex visualizations
- Incorporating additional datasets
- Performing time series analysis

