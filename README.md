# Country Comparison Analysis \| Power BI

An interactive Power BI project that compares countries across economic,
demographic, geographic, and health indicators. The dashboard brings key
country-level metrics together to help users explore differences in
development and performance across regions.

## Project Overview

This project uses a country-level dataset covering **191 countries** to
explore relationships and patterns across indicators such as GDP,
population, inflation, life expectancy, birth rate, and death rate.

The report is designed to support both high-level comparisons and more
detailed country-level exploration through KPI cards, rankings, tables,
charts, and geographic visuals.

## Dashboard Preview

### 1. Country Development & Economic Performance
<img width="1069" height="605" alt="Overview" src="https://github.com/user-attachments/assets/ff1e7a43-131f-4bd5-90fd-982df3ba1221" />

### 2. Health Analysis
<img width="1069" height="605" alt="Health Analysis" src="https://github.com/user-attachments/assets/d83fc1c6-a0d5-48a0-b731-de3f3213ba40" />

### 3. Economic Performance
<img width="1070" height="608" alt="Economic Performance Analysis" src="https://github.com/user-attachments/assets/d1fcc25b-ed77-4e23-a2a9-f944b3fd40f9" />

### 4. Geographic Analysis
<img width="1068" height="608" alt="Map" src="https://github.com/user-attachments/assets/90927190-b5f6-4da4-823d-297561d9f369" />


## Key Dashboard Highlights

-   **Total population:** 6.39 billion
-   **Average life expectancy:** 65.68 years
-   **Average GDP:** approximately \$287.73 billion
-   **Highest GDP country:** United States
-   **Lowest inflation country:** Nauru

## Analysis Areas

### 1. Country Development & Economic Performance

-   Compare country-level economic indicators.
-   Explore GDP and population distribution.
-   Review country rankings and key performance indicators.

### 2. Health Analysis

-   Compare life expectancy across countries.
-   Explore birth and death rate patterns.
-   Review HIV/AIDS indicators available in the dataset.

### 3. Economic Performance

-   Compare GDP, GDP per capita, GDP growth, and inflation.
-   Identify countries with higher and lower GDP growth.
-   Review country-level economic metrics in a comparative table.

### 4. Geographic Comparison

-   Explore the distribution of GDP, population, life expectancy, and
    inflation across countries and regions.
-   Use geographic visuals to identify regional patterns.

## Tools & Technologies

-   **Power BI Desktop** -- dashboard development and data visualization
-   **Power Query** -- data preparation, transformation, and merging
    queries
-   **DAX** -- measures and ranking calculations
-   **Microsoft Excel** -- supporting data review and preparation

## Data Preparation

The Power Query workflow included: - Promoting headers and assigning
data types. - Removing top rows and reorganizing columns where
required. - Merging queries to support country identification and
mapping, including the identification of independent countries. -
Expanding merged columns. - Adding conditional and custom columns. -
Filtering rows and replacing values where required. - Reviewing column
quality, distribution, and uniqueness.

## DAX Measures

The report uses DAX measures for aggregations and country rankings,
including:

-   Average Birth Rate
-   Average Death Rate
-   Average GDP
-   Average Life Expectancy
-   Average Inflation Rate
-   Total Population
-   GDP Rank
-   Inflation Rate Rank
-   Life Expectancy Rank
-   Trade Balance Rank

Ranking measures use `RANKX` with dense ranking. Aggregation measures
use functions such as `AVERAGE` and `SUM`; ranking logic also uses
functions such as `ALL`, `CALCULATE`, and `MAX`.

## Repository Structure

``` text
Country-Comparison-Analysis/
│
├── README.md
│
├── Country Comparison Analysis/
│   ├── Country Comparison Analysis.pbix
│   └── Country Comparison Analysis.pdf
│
├── Documentation/
│   ├── Business_Insights_Report.pdf
│   ├── DAX_Documentation.pdf
│   └── Data_Cleaning_Documentation.pdf
│
└── Images/
    ├── overview.png
    ├── health-analysis.png
    ├── economic-performance.png
    └── geographic-analysis.png
```

## Project Documentation

The `Documentation/` folder contains:

-   **Business Insights Report** -- summarizes the main dashboard
    findings and analytical observations. [Business_Insights_Report.pdf](https://github.com/user-attachments/files/35089250/Business_Insights_Report.pdf)

-   **DAX Documentation** -- lists the measures, formulas, and
    explanations. [DAX_Documentation.pdf](https://github.com/user-attachments/files/35089280/DAX_Documentation.pdf)

-   **Data Cleaning Documentation** -- outlines the Power Query workflow
    and data-quality checks. [Data_Cleaning_Documentation.pdf](https://github.com/user-attachments/files/35089289/Data_Cleaning_Documentation.pdf)


## Notes & Limitations

-   This is a country-level comparative analysis based on the fields
    available in the source dataset.
-   The dataset does not contain a Year field; therefore, the report
    should be interpreted as a cross-sectional comparison rather than a
    time-series analysis.
-   Three missing inflation-rate values were identified during data
    profiling. Review the cleaning documentation for details.
-   Results depend on the source data, data types, filters, and measure
    logic.
-   Include or redistribute the source dataset only if its license and
    terms permit it.

## Author

**Ahmed Mansour**\
Data Analyst \| Power BI • SQL • Excel

-   [LinkedIn](https://www.linkedin.com/in/ahmed-mansour-955aa0197)
-   [Portfolio](https://ahmedmansourdataanalyst.my.canva.site/ahmed-mansour)

------------------------------------------------------------------------

If you find this project useful, feel free to star the repository.
