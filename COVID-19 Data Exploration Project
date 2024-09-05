# COVID-19 Data Exploration Project

This project explores COVID-19 data using SQL queries to analyze various aspects such as infection rates, death rates, vaccination rates, and more. The dataset includes COVID-19 statistics by location, such as total cases, new cases, total deaths, population, and vaccination data.

## Skills Used

- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Converting Data Types

## Data Overview

The data used for this project comes from two tables: `CovidDeaths` and `CovidVaccinations`, both located in the `Testing` database. The `CovidDeaths` table contains data about COVID-19 cases, deaths, and population by location and date, while the `CovidVaccinations` table contains vaccination data.

## Key Analysis and Insights

### 1. Initial Data Inspection

- **Purpose:** To inspect and filter the initial dataset.
- **Method:** Queries were written to examine and select non-null continents to filter relevant data.
- **Fields Selected:** `Location`, `Date`, `Total Cases`, `New Cases`, `Total Deaths`, and `Population`.

### 2. Total Cases vs. Total Deaths

- **Purpose:** To determine the likelihood of dying if someone contracts COVID-19.
- **Calculation:** Death Percentage = `(Total Deaths / Total Cases) * 100`.
- **Filter:** The data is filtered for locations containing "states" to focus on specific regions.

### 3. Total Cases vs. Population

- **Purpose:** To analyze the infection rate.
- **Calculation:** Percentage of Population Infected = `(Total Cases / Population) * 100`.

### 4. Highest Infection Rates

- **Purpose:** To identify countries with the highest infection rates compared to their population.
- **Metrics:**
  - **Highest Infection Count:** Maximum number of cases recorded in each location.
  - **Percentage of Population Infected:** Maximum percentage of the population that was infected.

### 5. Highest Death Counts

- **Purpose:** To identify countries with the highest death counts relative to their population.
- **Metric:** Total Death Count - The maximum number of deaths recorded in each location.

### 6. Analysis by Continent

- **Purpose:** To understand the impact at the continental level.
- **Metrics:**
  - Total death counts per continent.
  - Breakdown to determine which continents had the highest death counts.

### 7. Global Analysis

- **Purpose:** To calculate global statistics.
- **Metrics:**
  - Total cases, total deaths, and death percentage worldwide.

### 8. Population vs. Vaccinations

- **Purpose:** To analyze vaccination progress by comparing the total population to the number of people vaccinated.
- **Method:** Uses window functions to calculate rolling totals of people vaccinated per location.

### 9. Using CTE (Common Table Expressions)

- **Purpose:** To compute the rolling total of vaccinated people and the percentage of the population vaccinated.
- **Benefits:** Provides a simplified approach to calculate and use complex aggregations within a single query.

### 10. Using Temporary Tables

- **Purpose:** To store intermediate results and perform calculations.
- **Method:** Creates a temporary table to calculate the rolling total of vaccinated people.
- **Benefits:** Allows for efficient calculations and querying in subsequent operations.

### 11. Creating Views for Future Analysis

- **Purpose:** To store the data for later use by creating a SQL view named `PercentPopulationVaccinated`.
- **Benefits:** Facilitates easier visualization and further analysis by storing complex SQL results in a reusable view.

## Summary

This project showcases different SQL techniques to analyze COVID-19 data effectively. The queries help in understanding the spread of the virus, the mortality rate, the impact on different continents, and the progress of vaccination efforts.

## Next Steps

- Integrate this analysis with visualization tools like Power BI or Tableau.
- Use the created SQL view for interactive dashboards and visual representations of the COVID-19 data.
