# Student Enrollment Funnel Analysis
**UCLA Master of Applied Statistics Thesis, 2023**

Logistic regression and exploratory data analysis on prospective student
touchpoints through enrollment and first-year completion at a small private
arts college.

---

## Overview

This study modeled the full student enrollment funnel — from initial marketing
contact through application, enrollment, and completion of the first academic
year. The goal was to estimate the likelihood of progression at each stage and
identify factors that predict drop-off.

Two audiences were in scope:

- **Marketing department** — identifying outreach channels by effectiveness
  relative to cost, to guide resource allocation
- **Student advising department** — identifying demographic and behavioral
  factors associated with increased drop-off risk at each stage of the funnel

---

## Methods

- **Exploratory data analysis** — distributions, missingness, demographic
  breakdowns across funnel stages
- **Logistic regression** — separate models for each transition in the funnel
  (contact → applicant, applicant → enrollee, enrollee → active, active →
  first-year completion)
- **Odds ratios and confidence intervals** — used to rank outreach touchpoints
  and identify significant predictors of drop-off

Key findings included poorly performing, resource-intensive outreach channels
that were outperformed by lower-cost alternatives, and demographic risk factors
that varied by funnel stage.

---

## Repository Contents

| File | Description |
|------|-------------|
| `MAS_Thesis_Bowne_2023.pdf` | Full published thesis |
| `analysis.R` | R code for data cleaning, EDA, and logistic regression models |

**Note:** The underlying dataset is not included. It contains student-level
records from a private institution and is not suitable for public distribution.
The code is documented to be readable without the data.

---

## Tools & Packages

- **R** — base stats, `dplyr`, `tidyverse`
- **Logistic regression** — `glm()` with binomial family
- **Visualization** — `ggplot2`

---

## Citation

Bowne, C. T. (2023). *Factors that contribute to student applicants achieving
and maintaining active status through the first academic year: a case study.*
Master's thesis, University of California, Los Angeles.
