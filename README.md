# COVID-19 Data Exploration Using SQL

## 📊 Project Overview

This project performs a deep exploration of COVID-19 datasets using SQL. The goal is to extract insights from COVID-related data across various countries and continents, using advanced SQL techniques.

### 🔧 Skills Demonstrated:
- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Views
- Data Type Conversion

---

## 📁 Dataset Tables Used

- `CovidDeaths`
- `CovidVaccinations`

These tables contain data on COVID-19 cases, deaths, vaccinations, and population metrics.

---

## 🔍 Key Insights

- Likelihood of death after contracting COVID-19 (case fatality rate)
- Infection rate compared to population
- Countries with highest infection and death counts
- Continental death totals
- Global COVID trends over time
- Rolling count of vaccinated individuals by country

---

## 🧠 SQL Concepts Applied

- `JOIN` operations to combine death and vaccination datasets
- `GROUP BY` and `ORDER BY` to aggregate and sort data
- `WINDOW FUNCTIONS` like `SUM() OVER (PARTITION BY ...)` to compute rolling values
- `CTEs` and `TEMP TABLES` for cleaner query structure and reuse
- `VIEWS` for persistent summarized outputs

---


## 🗂 File Structure

- `CovidDeaths.xlsx` – Raw data on COVID-19 cases, deaths, population
- `CovidVaccinations.xlsx` – Raw data on vaccinations per country and date
- `Covid Deaths Data Exploration Portfolio Project SQL.sql` – Full SQL script with queries and insights


---

## 📈 Next Steps

You can use this SQL output in a BI tool such as:
- **Tableau**
- **Power BI**
- **Excel** (via SQL import or CSV exports)

Create dashboards for:
- Vaccination trends
- Death rates per continent
- Daily new case trends
- Top 10 infected countries

---

## 🛠 Tech Stack

- SQL (Microsoft SQL Server)
- GitHub

---

## 🔗 How to Run

1. Import the COVID datasets into your SQL Server (tables: `CovidDeaths`, `CovidVaccinations`)
2. Run the SQL script provided
3. Optionally connect results to a BI tool for visualization

---

## 📂 Data Source

The original datasets used in this project are provided by [Our World in Data](https://ourworldindata.org/coronavirus):

You can access the cleaned Excel versions of the datasets here:

- [CovidDeaths - Google Sheet](https://docs.google.com/spreadsheets/d/18TAmz6x4TUQlacYAm0-zDLEY-hEHJClN/edit?usp=sharing&ouid=109068200435034755517&rtpof=true&sd=true)
- [CovidVaccinations - Google Sheet](https://docs.google.com/spreadsheets/d/1Mu-b9JY0SmSfpOPAiFKbZk5oHOdA-4CP/edit?usp=sharing&ouid=109068200435034755517&rtpof=true&sd=true)

