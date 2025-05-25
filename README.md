# Ice-cream-Analysis

Overview
This project explores the historical trends and forecasts of monthly ice cream production in the United States, using time series data from the Federal Reserve Economic Data (FRED). The dataset covers January 1972 to December 2024, and the goal is to model and understand the dynamics of ice cream manufacturing as well as predict production through December 2025.

Goals
	•	Describe and model the dynamics of US ice cream production.
	•	Forecast monthly production through December 2025.
	•	Provide insights for decision-making in the ice cream industry, including uncertainty bounds.

Data Source
	•	Dataset: IPN31152N.csv
	•	Source: Federal Reserve Bank of St. Louis (FRED)
	•	Series: Ice Cream and Frozen Desserts Manufacturing (NAICS 31152)
	•	Link: https://fred.stlouisfed.org/series/IPN31152N

Methodology
	1.	Data Exploration and Visualization
	•	Time series plot
	•	Relevant seasonal plot
	•	Decomposition plot
	•	ACF, PACF, and periodogram analysis
	2.	Seasonal Adjustment
	•	Standardize each month by its mean and standard deviation across years.
	•	Compare the unadjusted and seasonally adjusted series using plots.
	3.	Model Development
	•	Develop a SARIMA or trend-stationary SARMA model.
	•	Justify model choice using unit root tests, model selection criteria (AIC, BIC), and residual diagnostics.
	4.	Forecasting
	•	Forecast monthly ice cream production through December 2025.
	•	Include uncertainty bounds and assess the forecast’s validity.

Deliverables
	•	Plots and analysis of time series characteristics.
	•	Seasonally adjusted series and comparison with unadjusted data.
	•	Final SARIMA/SARMA model with justification and residual checks.
	•	Forecasted production with confidence intervals.
	•	Executive summary of insights for industry managers and analysts.

Target Audience
This report is designed for:
	•	Managers in ice cream manufacturing who need data-driven insights for production planning.
	•	Investment analysts interested in market trends and risks within the food production sector.
