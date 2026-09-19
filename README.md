# Quant Research Papers (Ordered for Beginners)

This repository reorganizes the papers from the source repository [`priyanshupriyank04/Quant_Research_papers`](https://github.com/priyanshupriyank04/Quant_Research_papers) into a **beginner-friendly learning sequence**.

## What this repository is for

- Give beginners a practical order for learning quantitative finance research.
- Move from research basics and numerical foundations to portfolio construction, signals, derivatives, risk, ML, and advanced theory.
- Keep original paper filenames and provide local links for direct reading.

## Important warnings

- These papers are for education and research, **not investment advice**.
- Mathematical depth varies a lot; some papers are intentionally placed later because they are more technical.

## Folder structure (learning phases)

- `00_orientation_research_methods`
- `01_numerical_mathematical_foundations`
- `02_portfolio_risk_optimization`
- `03_asset_allocation_portfolio_management`
- `04_empirical_research_trading_signals`
- `05_derivatives_volatility`
- `06_risk_management`
- `07_machine_learning_finance`
- `08_advanced_theory`

## Prerequisites and beginner learning goals

### Prerequisites

Before or during this reading path, review:
- basic probability and statistics (mean, variance, covariance, correlation)
- linear algebra basics (vectors, matrices)
- regression and optimization basics
- time-series returns and volatility concepts
- basic Python for finance (NumPy/pandas/matplotlib; optional scikit-learn)

### Beginner goals

By the end, you should be able to:
- read and critique empirical finance papers
- understand portfolio construction and rebalancing trade-offs
- interpret factor and signal-based results
- grasp options/volatility modeling intuition
- evaluate risks of quantitative strategies and model limitations

## Recommended reading order (all papers)

Each entry includes local paper link and why it appears at that point.

1. [`quantitative_research_methods.pdf`](./00_orientation_research_methods/quantitative_research_methods.pdf)  
   Why here: establishes how to frame questions, design studies, and interpret evidence before technical modeling.

2. [`numerical_methods_quantitative_finance.pdf`](./01_numerical_mathematical_foundations/numerical_methods_quantitative_finance.pdf)  
   Why here: introduces numerical tools used repeatedly in later optimization/pricing papers.

3. [`market based portfolio variance.pdf`](./01_numerical_mathematical_foundations/market%20based%20portfolio%20variance.pdf)  
   Why here: portfolio variance and covariance intuition is foundational for optimization and risk.

4. [`Minimum_variance_portfolio_construction.pdf`](./02_portfolio_risk_optimization/Minimum_variance_portfolio_construction.pdf)  
   Why here: first direct optimization application after risk/covariance fundamentals.

5. [`Indian_portfolio_optimization.pdf`](./02_portfolio_risk_optimization/Indian_portfolio_optimization.pdf)  
   Why here: applies optimization in a real market context and highlights practical constraints.

6. [`portfolio optimisation in python.pdf`](./02_portfolio_risk_optimization/portfolio%20optimisation%20in%20python.pdf)  
   Why here: connects portfolio theory to implementation-oriented workflow.

7. [`Portfolio_construction_black_litterman_model.pdf`](./02_portfolio_risk_optimization/Portfolio_construction_black_litterman_model.pdf)  
   Why here: best understood after standard mean-variance and estimation challenges.

8. [`Asset_allocation_using_stochastic_linear_programming.pdf`](./02_portfolio_risk_optimization/Asset_allocation_using_stochastic_linear_programming.pdf)  
   Why here: extends allocation into uncertainty-aware stochastic optimization.

9. [`quantitative_multi_asset_portfolio_management.pdf`](./03_asset_allocation_portfolio_management/quantitative_multi_asset_portfolio_management.pdf)  
   Why here: broadens to multi-asset portfolio construction once optimization basics are in place.

10. [`when-to-efficiently-rebalance-a-portfolio-xfla299ttj.pdf`](./03_asset_allocation_portfolio_management/when-to-efficiently-rebalance-a-portfolio-xfla299ttj.pdf)  
    Why here: builds practical portfolio maintenance intuition (turnover, costs, timing).

11. [`the_cross-section_of_expected_stock_returns.pdf`](./04_empirical_research_trading_signals/the_cross-section_of_expected_stock_returns.pdf)  
    Why here: core empirical asset-pricing framework for expected-return differences.

12. [`Quant_analysis_pricemomentum_indianmarkets.pdf`](./04_empirical_research_trading_signals/Quant_analysis_pricemomentum_indianmarkets.pdf)  
    Why here: concrete momentum signal study after learning cross-sectional return logic.

13. [`Opening-range research paper.pdf`](./04_empirical_research_trading_signals/Opening-range%20research%20paper.pdf)  
    Why here: intuitive event-window signal paper with approachable empirical framing.

14. [`Correlation between overnight returns and overnight news.pdf`](./04_empirical_research_trading_signals/Correlation%20between%20overnight%20returns%20and%20overnight%20news.pdf)  
    Why here: deepens event/news-return linkage once basic signal-testing ideas are familiar.

15. [`What happened to quants in august 07.pdf`](./04_empirical_research_trading_signals/What%20happened%20to%20quants%20in%20august%2007.pdf)  
    Why here: case-study on crowded trades, liquidity stress, and model-risk reality.

16. [`black_scholes73.pdf`](./05_derivatives_volatility/black_scholes73.pdf)  
    Why here: canonical derivatives model to anchor option-pricing intuition.

17. [`Forecasting_currency_options.pdf`](./05_derivatives_volatility/Forecasting_currency_options.pdf)  
    Why here: applies derivatives concepts to forecasting in FX options markets.

18. [`Options-driven volatility forecasting.pdf`](./05_derivatives_volatility/Options-driven%20volatility%20forecasting.pdf)  
    Why here: uses option information for volatility expectations after option basics.

19. [`stochastic_volatility_models.pdf`](./05_derivatives_volatility/stochastic_volatility_models.pdf)  
    Why here: technically heavier volatility dynamics, best after prior derivatives papers.

20. [`risk-factor-aggregation-and-stress-testing-2woi5ioh1j.pdf`](./06_risk_management/risk-factor-aggregation-and-stress-testing-2woi5ioh1j.pdf)  
    Why here: integrates risk factors and stress scenarios after portfolio/signal foundations.

21. [`price prediction using lstm and portfolio allocation.pdf`](./07_machine_learning_finance/price%20prediction%20using%20lstm%20and%20portfolio%20allocation.pdf)  
    Why here: first ML application once statistical and portfolio basics are already built.

22. [`approximation and regression using DNNs in finance.pdf`](./07_machine_learning_finance/approximation%20and%20regression%20using%20DNNs%20in%20finance.pdf)  
    Why here: deeper ML approximation/regression ideas after the lighter LSTM application.

23. [`dynamic asset pricing using alpha MEU model.pdf`](./08_advanced_theory/dynamic%20asset%20pricing%20using%20alpha%20MEU%20model.pdf)  
    Why here: advanced theoretical paper that fits best as a capstone.

## Core path (8–10 papers if you cannot read everything)

1. [`quantitative_research_methods.pdf`](./00_orientation_research_methods/quantitative_research_methods.pdf)
2. [`numerical_methods_quantitative_finance.pdf`](./01_numerical_mathematical_foundations/numerical_methods_quantitative_finance.pdf)
3. [`market based portfolio variance.pdf`](./01_numerical_mathematical_foundations/market%20based%20portfolio%20variance.pdf)
4. [`Minimum_variance_portfolio_construction.pdf`](./02_portfolio_risk_optimization/Minimum_variance_portfolio_construction.pdf)
5. [`portfolio optimisation in python.pdf`](./02_portfolio_risk_optimization/portfolio%20optimisation%20in%20python.pdf)
6. [`Portfolio_construction_black_litterman_model.pdf`](./02_portfolio_risk_optimization/Portfolio_construction_black_litterman_model.pdf)
7. [`the_cross-section_of_expected_stock_returns.pdf`](./04_empirical_research_trading_signals/the_cross-section_of_expected_stock_returns.pdf)
8. [`black_scholes73.pdf`](./05_derivatives_volatility/black_scholes73.pdf)
9. [`risk-factor-aggregation-and-stress-testing-2woi5ioh1j.pdf`](./06_risk_management/risk-factor-aggregation-and-stress-testing-2woi5ioh1j.pdf)
10. [`price prediction using lstm and portfolio allocation.pdf`](./07_machine_learning_finance/price%20prediction%20using%20lstm%20and%20portfolio%20allocation.pdf)

## How to read a research paper effectively (beginner method)

Use a two-pass process:

### Pass 1 (high-level, 20–40 min)
1. Title + abstract
2. Introduction and contribution claims
3. Figures/tables and headline results
4. Conclusion and limitations

Goal: understand the core question and what was found.

### Pass 2 (deep reading)
1. Data construction and sample period
2. Methodology and assumptions
3. Robustness checks / out-of-sample setup
4. Economic intuition and implementation limits

Goal: decide whether findings are credible and usable.

## Notes template (short)

```text
Paper:
Question:
Data:
Method:
Key variables/factors:
Main result:
Assumptions:
Limitations / failure modes:
Replication ideas (Python/backtest):
Actionable insight (if any):
```

## Source sync and limitations (copied vs linked)

- Source repository: <https://github.com/priyanshupriyank04/Quant_Research_papers>
- Total PDFs found in source root: **23**
- PDFs copied locally into this repository: **23**
- PDFs linked-only (not copied): **0**

No GitHub file-size/transfer limits blocked any required paper in this update.
