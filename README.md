# Energy Consumption Patterns among homeowners and renters using linear regression

**Research Question:** How does the association between dwelling size and annual household energy expenditure differ between renters and homeowners, after accounting for household size, building type, heating fuel, and climate?

## Overview 

A statistical regression analysis exploring the association of dwelling size and annual household energy expenditure using Linear Regression Analysis.

## Dataset

* **Source:** [U.S. EIA Residential Energy Consumption Survey (RECS) 2020, Public Use Microdata](https://www.eia.gov/consumption/residential/data/2020/)
* **Size:** 18,496 observations (households) across 799 variables; 17,571 observations in the analytic sample after filtering
* **Target Variable:** `TOTALDOL`, total annual household energy expenditure (USD), log-transformed for modeling
* **Key Predictors:** dwelling size (`TOTSQFT_EN`), tenure (`KOWNRENT`), household size (`NHSLDMEM`), building type (`TYPEHUQ`), main heating fuel (`FUELHEAT`), climate (`HDD65`, `CDD65`)
* **Survey design:** complex probability sample; 60 jackknife replicate weights (`NWEIGHT1`–`NWEIGHT60`) plus a final weight (`NWEIGHT`) representing about 123.5 million U.S. occupied housing units
* **License / access:** U.S. government data, publicly available from EIA
