# Mean-CVaR Portfolio Optimization using Linear Programming

This project formulates and solves a Conditional Value-at-Risk (CVaR)
minimization portfolio optimization problem using linear programming.

The model is applied to daily returns of major Indian equities and compared
against equal-weight portfolios under stress scenarios.

## Features
- CVaR minimization using convex optimization
- Stress testing under worst 5% market scenarios
- Comparison with naive equal-weight portfolios
- Tail-risk visualization

## Tech Stack
Python, NumPy, Pandas, CVXPY, yfinance, Matplotlib

## Results
The optimized portfolio consistently achieves lower downside risk compared
to equal-weight allocations.
