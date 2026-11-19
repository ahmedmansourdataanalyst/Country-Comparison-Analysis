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

> Add your dashboard screenshots to the `images/` folder and update the
> paths below.

  Dashboard Page                               Preview
  -------------------------------------------- -----------------------------------
  Country Development & Economic Performance   `images/overview.png`
  Health Analysis                              `images/health-analysis.png`
  Economic Performance                         `images/economic-performance.png`
  Geographic Comparison                        `images/geographic-analysis.png`

## Key Dashboard Highlights

-   **Total population:** 6.39 billion
-   **Average life expectancy:** 65.68 years
-   **Average GDP:** approximately \$287.73 billion
-   **Highest GDP country:** United States
-   **Lowest inflation country:** Nauru

*These figures reflect the values displayed in the project dashboard and
depend on the dataset and its aggregation logic.*

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

The main dataset contains 191 countries. Three missing values were
identified in the inflation-rate field. The project documentation
describes the visible cleaning workflow and its known limitations.

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

Refer to the DAX documentation in the repository for the full formulas
and explanations.

## Repository Structure

``` text
Country-Comparison-Analysis/
│
├── README.md
├── Country Comparison Analysis.pbix
├── Country Comparison Analysis.pdf
├── Country comparison cleaned.xlsx
│
├── Documentation/
│   ├── Business_Insights_Report.docx
│   ├── DAX_Documentation.docx
│   └── Data_Cleaning_Documentation.docx
│
└── images/
    ├── overview.png
    ├── health-analysis.png
    ├── economic-performance.png
    └── geographic-analysis.png
```

The `images/` folder is a suggested structure for dashboard screenshots.
Add the images before expecting the preview table to render.

## How to Explore the Project

1.  Download or clone this repository.
2.  Open `Country Comparison Analysis.pbix` using Power BI Desktop.
3.  If Power BI prompts for a data source, update the source path to the
    included Excel file (if you have permission to use the included data
    file).
4.  Refresh the data if required.
5.  Navigate through the report pages and interact with the available
    visuals and filters.

## Project Documentation

The `Documentation/` folder contains:

-   **Business Insights Report** -- summarizes the main dashboard
    findings and analytical observations.
-   **DAX Documentation** -- lists the measures, formulas, and
    explanations.
-   **Data Cleaning Documentation** -- outlines the Power Query workflow
    and data-quality checks.

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

-   [LinkedIn](https://www.linkedin.com/)
    `<!-- Replace with your LinkedIn profile URL -->`{=html}
-   [Portfolio](https://ahmedmansourdataanalyst.my.canva.site/ahmed-mansour)

------------------------------------------------------------------------

If you find this project useful, feel free to star the repository.
