# Exploring the Involvement in Freelancing and Tuition Activities of Students in SUST

![Project Type](https://img.shields.io/badge/Project-Statistical%20Analysis-blue)
![Institution](https://img.shields.io/badge/Institution-SUST-green)
![Sample Size](https://img.shields.io/badge/Sample-400%20Students-orange)
![Departments](https://img.shields.io/badge/Departments-17-informational)
![Model](https://img.shields.io/badge/Model-Binary%20Logistic%20Regression-purple)
![AUC](https://img.shields.io/badge/AUC-0.98-brightgreen)
![Accuracy](https://img.shields.io/badge/Accuracy-96.8%25-success)

A research project examining how and why students at **Shahjalal University of Science and Technology (SUST)** participate in **freelancing** and **private tuition** alongside their studies.

---

## Overview
This repository contains the materials for a quantitative study on student involvement in income-generating activities at SUST. The project focuses on measuring participation patterns, identifying associated factors, and building a predictive model to explain student involvement.

## Objectives
- Measure the prevalence of freelancing and private tuition among SUST students.
- Describe the socio-academic profile of selected respondents.
- Test associations between student characteristics and participation.
- Identify the strongest predictors of involvement using logistic regression.
- Translate survey data into actionable insights for student support and research.

## Study Design
| Item | Details |
|---|---|
| Institution | Shahjalal University of Science and Technology (SUST) |
| Study year | 2023 |
| Population | SUST students |
| Sampling frame | 27 departments across 6 schools |
| Selected departments | 17 departments |
| Sampling method | Probability Proportional to Size (PPS) + Simple Random Sampling (SRS) |
| Sample size | 400 students |
| Data collection | Direct interview-based survey |

## Tools and Methods
### Tools
- **IBM SPSS 25**
- **RStudio 4.3.1**

### Statistical techniques
- Descriptive statistics
- Crosstabulation
- Chi-square tests
- Binary multiple logistic regression
- VIF-based multicollinearity assessment
- Goodness-of-fit evaluation
- Hosmer-Lemeshow test
- ROC curve and AUC analysis
- Bar and pie chart visualization

## Key Results
### Participation breakdown
| Category | Count | Share |
|---|---:|---:|
| Tuition only / tuition-involved dominant group | 220 | 55.0% |
| Freelancing only | 23 | 5.75% |
| Both freelancing and tuition | 15 | 3.75% |
| No involvement | 142 | 35.5% |

### Model performance
| Metric | Value |
|---|---:|
| Classification accuracy | 96.8% |
| AUC | 0.98 |
| Nagelkerke R² | 0.912 |
| Hosmer-Lemeshow p-value | 0.977 |

## Key Insights
- **Tuition was the dominant earning activity**, with **220 out of 400 students (55.0%)** involved.
- **Freelancing participation was much lower** than tuition, suggesting tutoring remains the more accessible or familiar income source for students.
- Participation patterns varied across departments and student characteristics.
- **Time spent on income-generating work** emerged as one of the strongest predictors of participation in the final model.
- The model demonstrated **excellent discriminative performance**, showing that student involvement patterns can be predicted with high reliability from survey variables.

## Project Impact
This project converted student survey data into an evidence-based analytical framework for understanding work participation at SUST.

It can support:
- **student welfare planning** by showing how many students are actively engaged in paid work
- **career guidance initiatives** by revealing differences between freelancing and tuition pathways
- **policy discussion** around student financial pressure and earn-and-learn behavior
- **future research** on student labor participation across departments or universities

## Limitations
- The study is based on **self-reported survey responses**.
- It focuses on a **single university**, so findings may not generalize broadly.
- The design is **cross-sectional**, so causal conclusions should be avoided.
- Some socio-economic and behavioral factors may remain unobserved.

## Future Work
- Extend the study to multiple universities in Bangladesh.
- Compare findings across academic disciplines and regions.
- Add a fully reproducible R or Python workflow.
- Build an interactive dashboard for exploring the results.

## Author
**Md. Yeasir Zawad**  
Department of Statistics  
Shahjalal University of Science and Technology (SUST)
