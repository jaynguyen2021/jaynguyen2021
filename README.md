# Van Nguyen

Data Science student at The University of Texas at Dallas, graduating in December 2026.

I use Python, SQL, statistics, machine learning, and data visualization to analyze data and support practical business decisions. My main interests include data analytics, business intelligence, predictive modeling, and applied data science.

I am currently seeking entry-level opportunities in Data Analytics, Business Intelligence, Business Analytics, and Data Science.

U.S. permanent resident with unrestricted work authorization.

## Technical Skills

**Programming and Querying:** Python, SQL, R

**Data Analysis:** pandas, NumPy, exploratory data analysis, data cleaning, feature engineering

**Machine Learning:** scikit-learn, XGBoost, regression, classification, time-series forecasting, model evaluation, cross-validation

**Statistics:** statistical modeling, hypothesis testing, regression analysis, probability

**Data and Reporting Tools:** Power BI, Excel, DuckDB, Matplotlib

## Selected Projects

### Retail Operations Analytics and Multi-Store Sales Forecasting

Developed an end-to-end forecasting workflow for weekly retail sales at the Store x Department level using historical Walmart data.

The project focused on designing a realistic time-series evaluation process rather than using random train-test splits. I built exact-date lag and rolling features, compared machine-learning models with a strong 52-week seasonal-naive benchmark, and used chronological validation before evaluating the locked final holdout.

The final XGBoost forecasting procedure reduced Weighted Mean Absolute Error by **22.69%** compared with the seasonal-naive benchmark and performed better in **15 of 16 final holdout weeks**.

I also used SQL to build reporting views and created a three-page Power BI dashboard for historical sales, forecast performance, and forecast uncertainty.

**Tools:** Python, pandas, scikit-learn, XGBoost, statsmodels, DuckDB, SQL, Power BI

[View project](https://github.com/jaynguyen2021/retail-sales-forecasting)

### Customer Churn Prediction and Retention Policy

Built an end-to-end customer churn modeling workflow that connects model predictions to a practical customer-retention decision.

The project included leakage prevention, train-test separation, preprocessing pipelines, model comparison, cross-validation, probability evaluation, threshold selection, and model interpretation.

Because customer churn is an imbalanced classification problem, I focused on precision, recall, and PR-AUC rather than relying only on accuracy. I also evaluated different decision thresholds to show how model predictions could support a realistic retention policy under limited customer-contact capacity.

**Tools:** Python, pandas, scikit-learn, classification, cross-validation, model interpretation

[View project](https://github.com/jaynguyen2021/customer-churn-retention)

## How I Approach Data Work

I try to treat modeling as more than selecting an algorithm. My general workflow is to:

- understand the business question and define the decision the analysis should support;
- examine data quality and identify potential sources of leakage;
- choose validation methods that match how the model would actually be used;
- compare models against appropriate baselines;
- evaluate performance using metrics that fit the business problem;
- investigate where a model performs well and where it fails;
- communicate results through clear analysis, visualizations, and reporting.

## Current Focus

I am continuing to strengthen my skills in applied statistics, machine learning, SQL, forecasting, experimentation, and business analytics while preparing for early-career data roles.

I am particularly interested in positions where technical analysis can support forecasting, customer analytics, operations, reporting, or business decision-making.
