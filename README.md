# Exploring the Involvement in Freelancing/Tuition Activities of Students in SUST

This project investigates the prevalence, patterns, and determinants of student involvement in **freelancing** and **private tuition** at **Shahjalal University of Science and Technology (SUST), Bangladesh**.

## Overview
This repository contains the project materials for a quantitative study on how and why university students participate in income-generating activities alongside their academic work. The analysis focuses on identifying:

- how common freelancing and tuition activities are among SUST students
- which student characteristics are associated with participation
- which factors most strongly influence involvement
- how well a statistical model can predict participation

The project was completed as part of the **STA430 Project** course in the **Department of Statistics, SUST**.

## Key Findings
- Survey data were collected from **400 students** selected from **17 departments** across **6 schools**.
- **220 students (55.0%)** were involved in **tuition activities**.
- **23 students (5.75%)** were involved in **freelancing only**.
- **15 students (3.75%)** were involved in **both freelancing and tuition**.
- **142 students (35.5%)** reported **no involvement** in either activity.
- The final **binary logistic regression model** achieved **96.8% classification accuracy**.
- The model produced an **AUC of 0.98**, indicating excellent predictive performance.
- The model fit was strong, with **Nagelkerke R² = 0.912** and **Hosmer-Lemeshow p = 0.977**.

## Problem Statement
University students in Bangladesh increasingly participate in freelancing and private tuition to support their living costs, education expenses, and financial independence. This project examines the background characteristics, associations, and predictive factors behind that participation among SUST students.

## Objectives
- Assess the frequency of freelancing and tuition activities among SUST students.
- Describe the background characteristics of the selected students.
- Examine associations between student characteristics and participation.
- Identify the most influential factors affecting involvement.

## Methodology
### Study Design
- **Study population:** Students of Shahjalal University of Science and Technology (SUST)
- **Academic year:** 2023
- **Sampling frame:** 27 departments across 6 schools
- **Selected departments:** 17 departments using **Probability Proportional to Size (PPS)** sampling
- **Sample size:** 400 students
- **Respondent selection:** **Simple Random Sampling (SRS)**
- **Data collection:** Direct interview-based survey

### Tools Used
- **IBM SPSS 25** for data analysis
- **RStudio 4.3.1** for statistical analysis and modeling

### Statistical Techniques
- Descriptive statistics
- Bar charts and pie charts
- Crosstabulation
- Chi-square tests
- Binary multiple logistic regression
- VIF for multicollinearity assessment
- Goodness-of-fit evaluation
- Hosmer-Lemeshow test
- ROC curve and AUC-based model evaluation

## Results Summary
The study found that **tuition** was the most common student earning activity, far exceeding freelancing participation. Patterns varied by department, gender, extracurricular involvement, health behavior, and academic context.

Some notable findings include:
- Tuition was the dominant activity, suggesting it remains the most accessible and widely adopted earning option for students.
- Engagement patterns varied across disciplines, with some departments showing stronger freelancing participation and others depending more heavily on tutoring.
- Several student characteristics showed statistically significant association with participation, including gender and selected behavioral variables.
- Time spent on income-generating work emerged as one of the strongest predictors in the logistic regression model.

## Model Performance
The binary logistic regression model was used to predict whether a student was involved in freelancing/tuition activities.

Performance highlights:
- **Overall prediction accuracy:** 96.8%
- **Area Under Curve (AUC):** 0.98
- **Nagelkerke R²:** 0.912
- **Hosmer-Lemeshow test p-value:** 0.977

These metrics indicate that the model had **excellent discriminative ability** and **strong fit** for the observed data.

## Project Impact
This project turns survey data into evidence-based insight for understanding student work behavior at SUST. The findings can support:

- student welfare and financial assistance planning
- career guidance and skill development initiatives
- policy discussion around earn-and-learn activities
- future comparative research across universities in Bangladesh

## Limitations
As with most university survey-based studies, the findings should be interpreted in light of:
- self-reported student responses
- single-university scope
- cross-sectional design
- possible unobserved socio-economic or behavioral factors

## Future Work
- Extend the analysis to multiple universities in Bangladesh
- Compare departmental and regional differences at a larger scale
- Add reproducible scripts and documented data-processing steps
- Build a dashboard or interactive report for result exploration

## Author
**Md. Yeasir Zawad**  
Department of Statistics  
Shahjalal University of Science and Technology (SUST)
