# Skyline Capital Partners — Real Estate Investment Optimization

**Strategic Market Selection | Monte Carlo Simulation | Risk-Constrained Unit Mix Optimization**

## Project Overview

This project evaluates real estate investment opportunities through financial analysis, probabilistic simulation, and constrained optimization.

The objective is to identify an attractive investment market and determine a residential development mix that maximizes expected annual profit while accounting for demand uncertainty, space limitations, and downside risk.

## Business Objectives

- Compare potential real estate markets using investment performance and risk metrics.
- Evaluate expected returns through financial modeling.
- Simulate rental revenue and operating uncertainty using Monte Carlo methods.
- Optimize the allocation of studio and one-bedroom apartments.
- Test the recommended development strategy under increased vacancy assumptions.

## Methodology

### 1. Strategic Market Selection

Evaluated potential markets using financial performance indicators, including projected internal rate of return (IRR), to support market selection.

**Recommended market:** New Hope  
**Estimated mean IRR:** 8.8%

### 2. Monte Carlo Simulation

Modeled uncertainty in rental revenue, vacancy, and operating profitability through repeated simulated scenarios.

Simulation outputs include expected annual profit, profit volatility, downside profit estimates, and observed loss frequency.

### 3. Risk-Constrained Unit Mix Optimization

Compared feasible combinations of studio and one-bedroom apartments under development space and risk constraints.

**Optimal configuration:**

- 55 studio apartments
- 30 one-bedroom apartments
- 85 total units
- 80,000 square feet of allocated space

### 4. Vacancy Stress Testing

Evaluated the recommended configuration under a two-percentage-point increase in vacancy to assess its resilience to adverse operating conditions.

## Key Results

| Metric | Baseline | Vacancy Stress |
|---|---:|---:|
| Expected annual profit | $644,529 | $603,347 |
| Profit standard deviation | $122,340 | $117,927 |
| 5th-percentile profit | $435,570 | $399,554 |
| Observed simulated loss frequency | 0.00% | 0.00% |

The vacancy shock reduced expected annual profit by approximately **$41,182 (6.4%)**.

No losses were observed across the reported simulation scenarios. This does not imply that real-world losses are impossible.

## Technology Stack

- Python
- pandas and NumPy
- NumPy Financial
- SciPy
- Matplotlib
- Jupyter Notebook
- Monte Carlo simulation
- Financial modeling and constrained optimization

## Repository Contents

- `Skyline_Real_Estate_Optimization_Public.ipynb` — analytical methodology, saved visualizations, simulation results, and investment recommendations.
- `README.md` — project overview, methodology, findings, and limitations.
- `requirements.txt` — Python dependencies.
- `.gitignore` — excludes local files, environments, and the original course dataset.

## Data Availability

This project was developed using a dataset provided for academic coursework.

The original dataset is not distributed in this public repository because redistribution permission has not been confirmed.

The notebook retains selected aggregate results and visualizations for portfolio review. Full reproduction requires authorized access to the original dataset.

## Limitations

- Results depend on modeled assumptions regarding rent, vacancy, demand, and operating costs.
- Monte Carlo estimates represent simulated outcomes rather than guaranteed investment performance.
- Market selection and development recommendations are sensitive to the underlying financial assumptions.
- The original dataset is not publicly distributed, limiting independent reproduction.

## Potential Future Improvements

- Expand sensitivity analysis across additional economic and operating assumptions.
- Evaluate more severe vacancy and rental-rate stress scenarios.
- Incorporate additional investment-risk metrics.
- Compare alternative development strategies using multi-objective optimization.
- Automate scenario reporting through an interactive dashboard.

## Conclusion

The analysis identifies New Hope as the preferred investment market and recommends a development configuration of **55 studios and 30 one-bedroom apartments**.

The project demonstrates how financial modeling, Monte Carlo simulation, and constrained optimization can support risk-aware real estate investment decisions.
