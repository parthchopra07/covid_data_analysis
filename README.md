**COVID-19 Data Exploration Using SQL**

This project focuses on exploring and analyzing global COVID-19 data using **SQL Server**. The goal is to derive meaningful insights on infection rates, death rates, and vaccination progress using a variety of advanced SQL techniques.

* * * * *

**Project Highlights**

**Data Source**: Our World in Data - [COVID-19 Dataset](https://ourworldindata.org/covid-deaths)\
**Skills Used**:

-   SQL Joins
-   Common Table Expressions (CTEs)
-   Temp Tables
-   Window Functions
-   Aggregate Functions
-   Views
-   Data Type Conversion

* * * * *

**Key Analyses**

-   **Total Cases vs. Total Deaths**\
    Assesses death rates in different countries to show the likelihood of dying if infected.
-   **Infection Rate vs. Population**\
    Calculates what percentage of each country's population was infected.
-   **Highest Infection & Death Rates**\
    Identifies the countries and continents with the highest total cases and deaths per capita.
-   **Global Trends**\
    Summarizes global case and death totals with mortality percentages.
-   **Vaccination Progress**\
    Tracks vaccination rollouts and calculates rolling vaccination rates by country.

* * * * *

**Techniques Implemented**

-   Created **CTEs and Temp Tables** for complex calculations.
-   Used **Window Functions** for cumulative statistics (e.g., rolling vaccinations).
-   Created **SQL Views** for seamless visualization integration.
-   Applied **data filtering** to remove nulls and irrelevant entries (e.g., continent is not null).

* * * * *

**How to Use**

1.  Open the ```COVID19_DataExploration.sql``` file in SQL Server Management Studio (SSMS) or Azure Data Studio.
2.  Make sure your dataset tables are named ```CovidDeaths``` and ```CovidVaccinations```.
3.  Run queries step-by-step to explore data insights.
4.  Use the final **View** or **Temp Table** results to build dashboards in Tableau, Power BI, or Excel.

* * * * *

**Future Improvements**

-   Integrate visualizations using Tableau or Power BI.
-   Automate data pipeline with Python and schedule updates.
-   Include regional policy analysis and mobility data.

* * * * *

**Author**

**Parth Chopra**\
B.Sc Computer Science | AI & Data Engineering Specialist\
[LinkedIn](https://www.linkedin.com/in/parth-chopra07)

* * * * *

**License**

This project is licensed under the MIT License --- feel free to fork and contribute.
