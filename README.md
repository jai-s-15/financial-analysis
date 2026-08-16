# Financial Analysis Roadmap

A self-directed study working from quantitive market analysis toward systematic strategy research in Python. Each level pairs theoretical concepts and ideas with a project that implements it.


## Stages

| # | Project | Topic | Status |
|---|---------|-------|--------|
| 01 | [Return analysis](./01-return-analysis) | Analysis of asset returns: returns, volatility clustering, risk-adjusted performance | Complete |
| 02 | Data layer | Point-in-time price storage, corporate action adjustment, quality validation | Planned |
| 03 | Backtesting | Event driven simulation, look ahead bias, transaction costs | Planned |
| 04 | Volatility modelling | GARCH, stochastic volatility, forecast evaluation | Planned |
| 05 | Signal research | Cross-validation, labelling, limitations in financial ML | Planned |
| 06 | Portfolio construction | Mean-variance instability, covariance shrinkage, risk parity | Planned |
| 07 | Execution and risk analysis | Cost modelling, position sizing, drawdown control | Planned |

## Setup

```bash
pip install -r requirements.txt
```

Each project directory contains its own README and a notebook
demonstrating the analysis and code.

## Data

All projects use data from Yahoo Finance via `yfinance`. This carries natural
limitations that are documented per project.
