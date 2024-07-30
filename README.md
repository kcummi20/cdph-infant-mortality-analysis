# Racial/Ethnic Disparities in Infant Mortality: A Data Analysis with R

### Author: Katie Cummings
### Professor: Zhang
### Course: R for Programming
### Date: 6 May 2022

## Table of Contents

1. Introduction
2. Research Questions
3. Methods
4. Results
5. Discussion
6. How to Run the Code
7. Dependencies

## Introduction

The Chicago Department of Public Health (CDPH) is actively participating in a health improvement plan to promote health and racial/ethnic equity throughout the community. This project, part of the Health Chicago 2025 movement, focuses on the life expectancy of newborns, specifically analyzing racial and ethnic disparities in infant mortality rates in Chicago. The study aims to uncover trends in health outcomes and suggest interventions to improve the life expectancy of newborns in the non-Hispanic African American community.

## Research Questions
1. What are the average rates of infant health indicators for each race/ethnicity demographic in Chicago?
2. Which health predictor strongly influences disparate rates of infant mortality in Chicago?

## Methods
### Data Collection
The data for this project is sourced from the Illinois Department of Public Health (IDPH) and includes:
- Birth certificates
- Patient records from Chicago's 77 community areas

### Data Analysis
- **Tools Used:** R programming language in RStudio
- **Data Sources:** Chicago Health Atlas, IDPH’s Vital Statistics Records System.
- **Indicators Analyzed:**
  a) Infant mortality rate (number of infants who died per 1,000 live births)
  b) Access to prenatal care (percentage of births where mothers received early and adequate   
      prenatal care)
  c) Low birth weight rate (percentage of births where the infant weighed less than 2,500 
     grams)
  d) Preterm birth rate (percentage of births where gestational age was less than 37 weeks)

### Statistical Methods
1. Descriptive analysis and data visualization using line plots.
2. Conversion of various rates to a common scale.
3. Comparison of trends across different racial/ethnic demographics.
4. Scatterplots and Pearson’s correlation calculations to analyze relationships between indicators and infant mortality.

## Results
### Correlation Findings
- **Low Birth Weight and Infant Mortality**
  a) Non-Hispanic white infants: 0.505
  b) Non-Hispanic African American infants: 0.59
- **Preterm Birth and Infant Mortality:**
  a) Non-Hispanic white infants: 0.63
  b) Non-Hispanic African American infants: 0.63
- **Access to Prenatal Care and Infant Mortality:**
  a) Non-Hispanic white infants: 0.32
  b) Non-Hispanic African American infants: 0.16

## Discussion
The analysis reveals moderate correlations between preterm birth, low birth weight, and infant mortality rates in Chicago. The findings indicate significant racial/ethnic disparities, with non-Hispanic African American infants experiencing higher rates of mortality compared to their non-Hispanic white counterparts. These disparities highlight the need for targeted intervention strategies to reduce preterm births and low birth weight among non-Hispanic African American populations in Chicago.

## How to Run the Code
1. **Install R and RStudio:** Ensure that R and RStudio are installed on your machine.
2. **Install Required Packages:** Use the following R commands to install necessary packages:
  install.packages("ggplot2")
  install.packages("dplyr")
  install.packages("tidyr")
  install.packages("readr")
  install.packages("ggpubr")
3. **Load the Data:** Place the CSV files (infant mortality, prenatal care, low birth weight, preterm delivery) in your working directory.
4. **Run the Script:** Open the R script provided and execute it in RStudio to generate the analysis and visualizations.

## Dependencies
- R version 4.0.0 or higher
- RStudio version 1.2 or higher
- R Packages:
  ggplot2
  dplyr
  tidyr
  readr
  ggpubr

By following the instructions in this README, you can reproduce the analysis and explore the racial/ethnic disparities in infant mortality rates in Chicago. The findings aim to guide future public health interventions and improve health equity in the community.
  
