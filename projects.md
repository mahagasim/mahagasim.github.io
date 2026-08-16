---
layout: default
title: Projects & Analytical Work
---

# Projects & Analytical Work

<p class="page-intro">Public research, causal-inference, health-data, machine-learning, forecasting, NLP, and optimization projects. Each repository includes documentation of the analytical question, methods, results, limitations, and reproducibility workflow.</p>

<div class="project-entry">
  <div class="project-title">Causal Utility of Synthetic Health Data</div>
  <div class="project-meta">Causal Inference · Synthetic Health Data · Monte Carlo · Python · AIPW</div>

  <p>A semi-synthetic Monte Carlo study asking whether synthetic datasets that perform well on conventional statistical-fidelity diagnostics also preserve downstream causal analyses.</p>

  <p><span class="label">Main finding:</span> high conventional fidelity did not guarantee preservation of the causal treatment-effect analysis. Gaussian-copula synthetic data were difficult to distinguish from their matching reference data using standard diagnostics, while causal-estimate distortion and undercoverage remained, particularly under weak treatment overlap.</p>

  <p><span class="label">Methods:</span> simulated treatment and potential outcomes on empirical BRFSS covariates, Gaussian-copula synthesis, g-computation, IPW, cross-fitted AIPW, Monte Carlo evaluation, fidelity diagnostics, overlap stress testing, and inference calibration.</p>

  <a class="project-link" href="https://github.com/mahagasim/causal-utility-synthetic-health-data">View project repository</a>
</div>

<div class="project-entry">
  <div class="project-title">When Does Double Machine Learning Improve Causal Estimation?</div>
  <div class="project-meta">Causal Machine Learning · Double Machine Learning · Monte Carlo · Python</div>

  <p>A Monte Carlo benchmark studying how classical causal estimators and Double Machine Learning behave as confounding becomes high-dimensional, nonlinear, and difficult to represent, and as treatment overlap deteriorates.</p>

  <p><span class="label">Main finding:</span> DML did not automatically outperform simpler estimators. It performed well when the nuisance representation was adequate, while orthogonalization could not compensate for badly misspecified nuisance learners. Under nonlinear confounding, rich-dictionary DML sharply reduced bias relative to raw-linear alternatives; weak overlap still degraded inference.</p>

  <p><span class="label">Methods:</span> four simulation scenarios, manual cross-fitting and Neyman-orthogonal scores, LASSO nuisance learning, high-dimensional nonlinear feature dictionaries, OLS, IPW, AIPW, Monte Carlo bias/RMSE/coverage analysis, and overlap diagnostics.</p>

  <a class="project-link" href="https://github.com/mahagasim/double-ml-health-data-benchmark">View project repository</a>
</div>

<div class="project-entry">
  <div class="project-title">Factors Influencing Adult Obesity in the United States</div>
  <div class="project-meta">Health Data Science · R · Stata · BRFSS 2022</div>

  <p>Analysis of the 2022 Behavioral Risk Factor Surveillance System examining demographic, socioeconomic, behavioral, and health factors associated with adult obesity in the United States.</p>

  <p><span class="label">Methods:</span> descriptive and probability analysis, binary and multivariable logistic regression, multinomial and ordinal logistic regression, generalized linear mixed modelling with a state-level random intercept, and model comparison using AIC/BIC and likelihood-ratio tests.</p>

  <p><span class="label">Data:</span> 445,132 observations in the initial public-use BRFSS extract and 39,551 observations in the final analytical sample.</p>

  <p><span class="label">Context:</span> originally completed as a Health Data Science group project with Amal Ahmed and Arnela Halili; later reorganized and audited for reproducibility and documentation.</p>

  <a class="project-link" href="https://github.com/mahagasim/adult-obesity-brfss-analysis">View project repository</a>
</div>

<div class="project-entry">
  <div class="project-title">UN General Debate NLP & Machine Learning</div>
  <div class="project-meta">NLP · Topic Modelling · Machine Learning · Network Analysis · Python</div>

  <p>An Africa–Europe comparison using the United Nations General Debate Corpus, extended with Africa-focused topic modelling, sentiment analysis, and country-mention network analysis.</p>

  <p><span class="label">Scope:</span> the computational snapshot contains 7,507 speeches from 1970–2015, including 2,159 African and 1,667 European speeches in the main comparative sample.</p>

  <p><span class="label">Methods:</span> TF-IDF and cosine similarity, LDA, NMF, BERTopic, K-means clustering, LSTM classification, sentiment analysis, exploratory text analysis, and network analysis. The portfolio audit explicitly separates coursework-reported outputs from reconstructed and methodologically corrected results.</p>

  <a class="project-link" href="https://github.com/mahagasim/topic_modeling_UN_Data">View project repository</a>
</div>

<div class="project-entry">
  <div class="project-title">Retail Store Staff Scheduling Optimization</div>
  <div class="project-meta">Operations Research · Mixed-Integer Optimization · Python · Pyomo / HiGHS</div>

  <p>A mixed-integer staff-scheduling project reconstructed from MSc Managerial Decision Making and Modelling coursework, with a validated formulation covering staffing requirements, availability, skill constraints, rest rules, costs, and workload equity.</p>

  <p><span class="label">Main finding:</span> the corrected model satisfies the full 21-day staffing plan without temporary workers. A 5.8% increase in regular labor cost reduces the workload range from 12 days under the cost-priority solution to 1 day under the fairness-priority solution.</p>

  <p><span class="label">Methods:</span> binary/integer decision variables, coverage and skill constraints, rolling rest constraints, lexicographic optimization, cost minimization, and workload-equity optimization.</p>

  <a class="project-link" href="https://github.com/mahagasim/staff_scheduling_optimization_pyomo">View project repository</a>
</div>

<div class="project-entry">
  <div class="project-title">Tourism Forecasting Competition — 518 Annual Time Series</div>
  <div class="project-meta">Forecasting · Time Series · R · Python · Model Validation</div>

  <p>An audited reconstruction of MSc Predictive Business and Finance coursework comparing simple forecasting rules across 518 heterogeneous annual tourism-demand series.</p>

  <p><span class="label">Main finding:</span> a 5.5% growth-adjusted naive forecast achieved the lowest average validation error among the three benchmark rules, with 20.52% MAPE versus 20.87% for the flat naive forecast and 29.98% for a fitted linear trend. Forecast error increased substantially with the prediction horizon.</p>

  <p><span class="label">Methods:</span> series-specific train/validation splitting, naive and growth-adjusted forecasting, linear-trend extrapolation, MAPE and MASE evaluation, horizon-specific error analysis, and audit of the original coursework workflow.</p>

  <a class="project-link" href="https://github.com/mahagasim/Business-Project-monte-carlo-or-bayesian">View project repository</a>
</div>
