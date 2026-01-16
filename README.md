# Selected Quantitative Research

This repository contains selected academic and applied research in
quantitative finance, econometrics, and machine learning.

## Papers
### 1. Economic Policy Uncertainty and Industry Portfolio Volatility
- Methods: GARCH, macro–finance econometrics, volatility forecasting
- Tools: R
- [Paper (PDF)](./economic-policy-uncertainty-volatility/paper.pdf)

### 2. Fragility of Short Volatility Strategies
- Methods: Black–Scholes, stochastic calculus, options Greeks, Monte Carlo simulation
- Focus: Model risk, tail risk, convexity
- [Paper (PDF)](./options-strategy-fragility/paper.pdf)

### 3. LLM-Based Text Signals in Equity Return Prediction
- Data: SEC 10-K, 10-Q, and 8-K filings for S&P 500 firms; firm-specific financial news headlines
- Methods: Large language model–based feature extraction from regulatory disclosures; FinBERT sentiment scoring; supervised machine learning for multi-horizon return prediction; event-driven and long–short portfolio construction
- Validation: Time-based train–test splits to prevent information leakage; performance evaluation accounting for turnover and implementation realism
- Benchmark: Fama–French Five-Factor (FF5) model
- Key Findings: Filing-based LLM signals generate statistically meaningful returns largely orthogonal to traditional factor exposures, while news-based signals exhibit strong but short-lived predictability and out-of-sample fragility
- Contribution: Demonstrates that unstructured text provides incremental information when integrated with, rather than replacing, traditional quantitative asset pricing models
- [Paper (PDF)](./large-language-model-sec-filings/paper.pdf)
