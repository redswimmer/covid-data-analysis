# COVID-19 Data Analysis in R

## Overview

This project analyzes U.S. COVID-19 time series data from the Johns Hopkins University Center for Systems Science and Engineering (CSSE) to better understand the factors contributing to COVID-19 deaths. It also incorporates vaccination data from the GovEx repository to enhance predictive modeling.

As of March 10, 2023, the Johns Hopkins Coronavirus Resource Center ceased collection and reporting of global COVID-19 data, making this analysis a retrospective look at pandemic trends.

## Goals

- Explore trends in COVID-19 cases and deaths across U.S. states.
- Build linear regression models to understand the relationship between case counts and mortality.
- Incorporate vaccination data to assess its impact on COVID-19 outcomes.
- Identify bias and limitations in the available data.

## Data Sources

- **COVID-19 Time Series (Cases & Deaths)**  
  Source: [Johns Hopkins CSSE GitHub](https://github.com/CSSEGISandData/COVID-19)

- **Vaccination Data**  
  Source: [GovEx GitHub](https://github.com/govex/COVID-19)

## How to Run the Analysis

1. Clone the repository (or download the project folder):
   ```bash
   git clone https://github.com/your-username/covid19-data-analysis.git
   ```
2. Open RStudio and load the project folder.
3. Install required packages (if not already installed):
   ```R
   install.packages(c(
  "ggplot2",
  "lubridate",
  "corrplot",
  "tidyverse"
  ))
  ```
 4. Run the R Markdown file.