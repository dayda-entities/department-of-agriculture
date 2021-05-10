---
title: Novel Hurricane Hypothesis Predicts US Cattle Fever Tick Outbreaks
created: '2020-11-10T16:26:57.951643'
modified: '2020-11-10T16:26:57.951654'
state: active
type: dataset
tags:
  - Cattle Fever Tick Prediction
  - Cattle Tick
  - Disease
  - Np104
groups: []
csv_url: 'https://data.nal.usda.gov/system/files/COMMONS%20DATA.csv'
json_url: ''
layout: post

---
<p>Data Sources: Time series data on cattle fever tick incidence, 1959-2017, and climate variables January 1950 through December 2017, form the core information in this analysis. All variables are monthly averages or sums over the fiscal year (FY), October 01 (of the prior calendar year, y-1) through September 30 of the current calendar year (y). Annual records on detections of <em>Rhipicephalus (Boophilus) microplus</em> and <em>R. (B). annulatus</em> (cattle fever tick, CFT) on premises within the Permanent Quarantine Zone (PQZ) were obtained from CFTEP (USDA-APHIS and the USDA- ARS). Details of tick survey procedures, CFTEP program goals and history, and the geographic extent of the Permanent Quarantine Zone are in SI (Introduction, details). Solar radio flux data as well as Pacific Ocean El Niño Oscillation index data, 1950-2017, are accessed at from NOAA ESRL (2018b). Predicted values for on-going Solar Cycle 24 are from NOAA SWPC (2018). Accumulated Cyclone Energy Index (ACE) data are from the NOAA ESRL (2018a) database. Hurricane incidence data over the PQZ are accessed at the NOAA (2018) tropical storm database.</p>
<p>Local meteorology data are from the NOAA NCDC (2018) climate portal for three weather stations (Del Rio International Airport TX, Laredo Municipal Airport TX, and Brownsville South Padre Island International Airport TX). Details on these stations and data are in the SI (Methods and Data, additional details).</p>
<p>Data Pre-treatment: Global climate indicators, local meteorology, and CFT variables are assembled into a single MS Excel matrix. To address the low signal-to-noise ratio and non-independence of time series common in weather data (SI Methods and Data, additional details, tests). We transform all predictor and response variables using a series of five consecutive steps: 1) first differences (year n minus year n-1) were calculated; 2) and these converted to z scores (z = (x- μ) / σ); 3) linear regression was used to remove directional trends; 4) moving averages were calculated for each data vector, and; 5) a lag was optionally applied. The transformed data variables were then tested for predictive ability using simple correlation, probability of, error and level of significance.</p>
<p>Bivariate and Multivariate Regression Analysis: Four bivariate Best Model regressions of climate predictors on CFT are developed using XLSTAT software (Addinsoft Inc. 2018); three multivariate models include regression with no interactions, with level 2 interactions, and with variables restricted to two and to four variables minimum. To validate each model, we withhold the first and last 29 observations points. Nine model evaluation and three summary statistics are identified in SI (Methods and Data, additional details, definitions).</p>
<p>Reconstruction of Complete CFT Cycle, and Projection: It is generally recognized that the onset year of the first outbreak is not 1959 but some earlier point in the decade. Likewise, 2017 is unlikely the final end-year of the current outbreak. Given the lack of complete data on any one CFT outbreak cycle, we average CFT levels over Outbreak 1 and Outbreak 2, using 1987 as the mid-point between outbreaks (see Fig. 2). Using a Hurricane-Hale Cycle construct (SI Fig. 1), we hypothesize Outbreak 1 starts in 1943 and ends in 1987; Outbreak 2 starts in 1987 and ends in 2030-2031. We then extend the full CFT pattern one cycle into the future to forecast likely incidence beyond 2030.</p>

