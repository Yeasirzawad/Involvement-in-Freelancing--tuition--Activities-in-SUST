# What drives students to earn while studying?

![Project Type](https://img.shields.io/badge/Project-Statistical%20Analysis-blue)
![Institution](https://img.shields.io/badge/Institution-SUST-green)
![Sample Size](https://img.shields.io/badge/Sample-400%20Students-orange)
![Departments](https://img.shields.io/badge/Departments-17-informational)
![Model](https://img.shields.io/badge/Model-Binary%20Logistic%20Regression-purple)
![AUC](https://img.shields.io/badge/AUC-0.98-brightgreen)
![Accuracy](https://img.shields.io/badge/Accuracy-96.8%25-success)

Most student income conversations are based on assumptions.
This project turned that into data.

I analyzed survey responses from **400 students across 17 departments at SUST** to understand who gets involved in **freelancing and private tuition**, what factors drive that involvement, and how reliably those patterns can be predicted.

The result was a statistical study and logistic regression model with **96.8% classification accuracy** and **AUC = 0.98**, showing that **private tuition was the dominant income activity (220 students, 55%)** and that **time spent on income-generating work** was one of the strongest predictors of participation.

---

## Why this project matters
Students often balance academic pressure with financial pressure, but universities rarely have a clear, evidence-based picture of how students actually participate in earning activities.

This project addresses that gap by answering questions like:
- How common are freelancing and tuition among SUST students?
- Which activity is more dominant?
- Which academic or behavioral factors are most associated with participation?
- Can those patterns be modeled reliably using survey data?

This was not just a descriptive survey. It was an attempt to turn student behavior into a measurable, interpretable, and predictive analysis.

---

## What I built
I designed and completed a full statistical analysis workflow for this study:

- selected departments using **Probability Proportional to Size (PPS)** and **Simple Random Sampling (SRS)**
- collected primary survey data from **400 students**
- analyzed participation patterns with descriptive statistics and chi-square tests
- built a **binary multiple logistic regression model** to identify the strongest predictors of involvement
- evaluated model quality using **classification accuracy, ROC-AUC, Nagelkerke R², and Hosmer-Lemeshow goodness-of-fit**

This project combined survey methodology, inferential statistics, and predictive modeling in one end-to-end academic analysis.

---

## Key outcomes
### Participation breakdown
| Category | Count | Share |
|---|---:|---:|
| Tuition only / tuition-dominant group | 220 | 55.0% |
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

### What the numbers mean
- **Tuition clearly dominated** as the most common student earning pathway.
- **Freelancing participation was much lower**, suggesting barriers such as access, skills, or opportunity.
- **Time spent on income-generating work** emerged as one of the strongest predictors of participation.
- The final model showed that student involvement patterns were **highly predictable from survey variables**, not random or anecdotal.

---

## Project impact
This project made student earning behavior easier to understand, quantify, and discuss with evidence.

It created value in four ways:

1. **Measurement**  
   It quantified the scale of student involvement instead of relying on assumption.

2. **Clarity**  
   It showed that tuition, not freelancing, was the dominant income activity among surveyed students.

3. **Prediction**  
   It demonstrated that participation patterns could be modeled with strong statistical performance.

4. **Decision support**  
   The findings can support conversations around student welfare, income pressure, work-study balance, and future campus-level research.

---

## Portfolio summary
Analyzed survey data from **400 students across 17 departments** at SUST to identify the main factors influencing involvement in freelancing and private tuition. Built a binary logistic regression model with **96.8% classification accuracy** and **0.98 AUC**, revealing that tuition was the dominant earning activity (**220 students, 55%**) and that time spent on income-generating work was one of the strongest predictors of participation.

---

## Tools and methods
### Tools
- **IBM SPSS 25**
- **RStudio 4.3.1**

### Methods
- Descriptive statistics
- Crosstabulation
- Chi-square tests
- Binary multiple logistic regression
- Multicollinearity assessment using VIF
- ROC curve and AUC analysis
- Goodness-of-fit testing
- Data visualization with bar and pie charts

---

## Study design
| Item | Details |
|---|---|
| Institution | Shahjalal University of Science and Technology (SUST) |
| Study type | Cross-sectional survey-based statistical study |
| Sampling frame | 27 departments across 6 schools |
| Selected departments | 17 departments |
| Sampling method | Probability Proportional to Size (PPS) + Simple Random Sampling (SRS) |
| Sample size | 400 students |
| Data collection | Direct interview-based survey |

---

## Repository structure
```text
Involvement-in-Freelancing--tuition--Activities-in-SUST/
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── analysis.ipynb
├── scripts/
│   └── logistic_regression_analysis.R
├── reports/
│   └── project_report.pdf
├── figures/
│   ├── charts/
│   └── tables/
└── results/
    └── model_outputs/
```

If your actual folder names differ, replace this block with the real repository tree.

---

## What I learned
This project strengthened my ability to:
- design and analyze survey-based studies
- move from descriptive statistics to predictive modeling
- evaluate model quality beyond accuracy alone
- interpret student behavior using both statistical evidence and real-world context
- communicate research findings in a portfolio-ready, decision-oriented way

---

## Limitations
- The study uses **self-reported survey responses**.
- The sample is limited to **one university**, so findings should not be generalized too broadly.
- The design is **cross-sectional**, so the project identifies associations rather than causal effects.
- Some economic, behavioral, or family background variables may remain unobserved.

---

## Future improvements
- Extend the study to multiple universities in Bangladesh
- Add a fully reproducible R or Python workflow
- Include cleaned datasets and reusable analysis scripts
- Build an interactive dashboard for exploring results
- Compare participation patterns across departments and academic years

---

## Author
**Md. Yeasir Zawad**  
Department of Statistics  
Shahjalal University of Science and Technology (SUST)
