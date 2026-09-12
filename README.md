# Institutional Predictors of First-Year Student Retention in U.S. Higher Education
A project using IPEDS data and OLS regression to model the institutional factors that most contribute to first-year student retention rates at U.S. universities. Found that institutional grant coverage was the strongest predictor, suggesting affordability plays a significant role in whether students return for their second year.

## Repository Structure
- `data/raw/` — original IPEDS data files
- `data/processed/` — cleaned datasets used in modeling
- `data/data_dictionary.md` — variable definitions
- `notebooks/` — data cleaning, modeling, and visualization code
- `figures/` — exported charts and visualizations

## Future Work
Though this was originally for my M.S. capstone, I intend to expand the study:
- Extend the data timeline — incorporate longitudinal data back to the early 2000s instead of a single-year (2023-24) snapshot, to capture trends over time and reduce noise from any one year's anomalies (including possible lingering COVID-era effects)
- Re-test out-of-state cost of attendance — reintroduce this variable (excluded early on for collinearity) using an alternative model specification, since it showed modest predictive value and statistical significance; also re-examine how it interacts with institutional grant average, since including it seemed to shift that variable's apparent role
- Supplement IPEDS with qualitative/survey data — bring in student surveys or program audits to capture factors IPEDS doesn't report, like advising quality, campus culture, mental health support, and faculty engagement — particularly to explain why the part-time model failed to generalize
