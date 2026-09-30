# Time Series Projects

Two course projects applying statistical methods to economic and financial time series. Each project includes a runnable notebook, the datasets it uses, and selected figures.

| Project | Methods |
|---|---|
| [Midterm project](midterm_project/README.md) | GDP forecasting with ARIMA, volatility modeling with GARCH, seasonal housing sales with SARIMA |
| [Final project](final_project/README.md) | Kalman filtering, Gibbs sampling for a Markov-switching GARCH model, VAR diagnostics and cointegration |

## Run the notebooks

Use Python 3.10 or later. Install the shared dependencies from this repository's root: `pip install -r requirements.txt`. Start each notebook from its own project directory so its relative data paths resolve correctly:

```bash
cd midterm_project
jupyter lab analysis.ipynb
```

The final project uses MCMC and can take longer to run. Its generated sampler cache is kept under `.cache/` and is excluded from Git. Notebook figures are included as image files for quick browsing; running the notebooks recreates the plots inline.
