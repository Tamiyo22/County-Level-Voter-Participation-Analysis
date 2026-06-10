# County-Level Voter Participation Analysis (2020–2024)

## Overview

This project examines changes in county-level voter participation between the 2020 and 2024 United States presidential elections.

Using publicly available election returns from the MIT Election Data and Science Lab (MEDSL) and county-level demographic and socioeconomic indicators from County Health Rankings, the analysis explores patterns associated with increases and decreases in electoral participation across U.S. counties.

The goal of the project is not to determine causation, but rather to identify meaningful relationships and trends that may help explain differences in voter participation at the county level.

---

## Research Questions

This project seeks to answer the following questions:

* How did voter participation change between the 2020 and 2024 presidential elections?
* Which counties experienced the largest increases in participation?
* Which counties experienced the largest decreases in participation?
* What county characteristics are associated with higher voter participation?
* What county characteristics are associated with changes in participation over time?

---

## Data Sources

### Election Data

**MIT Election Data and Science Lab (MEDSL)**

Dataset:

* County Presidential Returns (2000–2024)

Variables used:

* County FIPS Code
* County Name
* State
* Election Year
* Total Votes Cast

### County Characteristics

**County Health Rankings**

Variables used:

* High School Completion
* Some College
* Median Household Income
* Children in Poverty
* Homeownership
* Broadband Access
* Percent Rural
* Percent Age 65 and Older
* Population

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook

---

## Methodology

### 1. Data Preparation

Election results were aggregated to the county level using total presidential votes cast in each county.

County FIPS codes were cleaned and standardized to ensure consistency across datasets.

### 2. Participation Change Calculation

For each county:

**Raw Vote Change**

2024 Total Votes − 2020 Total Votes

**Percent Change**

(2024 Votes − 2020 Votes) ÷ 2020 Votes

Both measures were analyzed because percentage change can exaggerate differences in counties with very small populations.

### 3. Exploratory Data Analysis

The analysis included:

* Summary statistics
* Distribution analysis
* Correlation analysis
* County-level comparisons
* Identification of counties with the largest increases and decreases in participation

### 4. County Characteristics Analysis

County-level demographic and socioeconomic variables were examined to identify relationships with voter participation.

---

## Preliminary Findings

### Participation Distribution

Most counties experienced relatively small changes in voter participation between 2020 and 2024.

The distribution was centered near zero, suggesting that participation levels remained relatively stable for many counties.

### Education

Counties with higher levels of educational attainment tended to have higher voter participation.

### Income

Median household income showed a positive relationship with turnout.

### Poverty

Counties with higher rates of child poverty tended to have lower voter participation.

### Broadband Access

Broadband availability showed a moderate positive relationship with participation, suggesting that access to information and online resources may be associated with civic engagement.

---

## Limitations

Several limitations should be considered:

* Correlation does not imply causation.
* County-level data may hide important local variation.
* The analysis uses total votes cast as a proxy for participation rather than official turnout rates.
* Some changes may reflect population growth, migration, or administrative factors rather than changes in voter behavior.
* Additional years of data would provide a stronger basis for identifying long-term trends.

---

## Future Improvements

Planned enhancements include:

* Regression modeling
* State-level comparisons
* Additional demographic variables
* Geographic visualizations
* Time-series analysis using earlier election cycles
* Enhanced reporting and documentation

---

## Author

Melissa Hargis

GitHub: https://github.com/Tamiyo22

LinkedIn: https://linkedin.com/in/melissa-hargis

Portfolio: https://melissahargis.netlify.app
