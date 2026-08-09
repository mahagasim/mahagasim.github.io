---
layout: default
title: Projects
---

# Projects

<p class="page-intro">Selected technical work demonstrating applied data analysis, statistical modelling, reproducible workflows, and responsible use of real-world data.</p>

## Factors Influencing Adult Obesity in the United States

**Health Data Science · BRFSS 2022 · R · Stata**

I analysed the 2022 **Behavioral Risk Factor Surveillance System (BRFSS)** to study demographic, socioeconomic, behavioral, and health factors associated with adult obesity in the United States.

The project demonstrates a complete applied workflow: data extraction, cleaning and recoding, descriptive analysis, probability analysis, statistical modelling, model comparison, multilevel analysis, diagnostics, visualization, and interpretation.

### Data and workflow

- **445,132** observations in the initial BRFSS working extract
- **39,551** observations in the final analytical sample
- public-use health survey data from the U.S. CDC
- reproducible Stata-to-R workflow

### Methods

- exploratory and descriptive analysis
- joint and conditional probability analysis
- binary logistic regression
- multivariable logistic regression
- multinomial logistic regression
- three ordinal logistic model specifications
- generalized linear mixed model with a **state-level random intercept**
- AIC/BIC model comparison and likelihood-ratio testing

### Selected results

- observed obesity prevalence was highest among adults aged **40–54 (44.9%)** in the filtered analytical sample
- women had a higher observed obesity rate (**42.3%**) than men (**37.4%**)
- the analysis identified meaningful variation across states and territories
- the mixed-effects model separated individual-level associations from residual state-level heterogeneity

### Attribution and reproducibility

I completed the original Health Data Science coursework as a group project with **Amal Ahmed and Arnela Halili**. I later reorganized my project materials into a reproducible GitHub repository and audited the outputs for consistency and documentation.

**Skills demonstrated:** R, RMarkdown, Stata, health-data preparation, regression modelling, mixed-effects models, model comparison, visualization, reproducibility, data provenance, and responsible public-health data handling.

[View the GitHub repository](https://github.com/mahagasim/adult-obesity-brfss-analysis)

---

Additional MSc projects will be added as I complete their reproducibility and documentation review.
