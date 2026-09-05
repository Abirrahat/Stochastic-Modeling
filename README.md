### Project Overview
This project develops and evaluates a regime-based asset allocation
strategy using VIX market volatility information.

The analysis considers:
- TLT – U.S. Treasury ETF
- GLD – Gold ETF
- SPY – S&P 500 ETF
- VIX – CBOE Volatility Index

### Methodology
The project includes:
- Daily log-return analysis
- Discrete Markov Chain regime classification
- 2-State and 3-State Gaussian Hidden Markov Models
- Model comparison using Log-Likelihood, AIC, and BIC
- State-conditional ETF return analysis
- Regime-based portfolio rotation
- One-day execution lag
- Backtesting against monthly equal-weight and SPY buy-and-hold benchmarks
- Sensitivity analysis to the number of states

### Files
- `Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.ipynb` – Executable Jupyter Notebook
- `Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.html` – HTML notebook output
- `Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.pdf` – Final report

### Data Source
Market data were obtained from Yahoo Finance.

4.	Check the notebook on GitHub. GitHub normally renders .ipynb notebooks directly in the browser, so after uploading it, click the notebook filename and verify that the code, graphs, tables, and explanations are visible. I strongly recommend uploading the executed notebook, because your assignment requires the code outputs to be included. 
5.	Optionally publish the HTML as a live webpage. If you want people to open your project like a website, rename a copy of your HTML file to index.html, upload it to the repository, then go to Settings → Pages. Under Build and deployment, choose Deploy from a branch, select main and /root, and save. Your project can then have a public webpage in addition to the normal GitHub repository. 
For your submission, I would structure the repository roughly as:
Stochastic-Modeling/
│
├── README.md
├── Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.ipynb
├── Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.html
├── Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.pdf
└── report/
    └── Regime-Based Asset Allocation using Markov Chains and Hidden Markov Models.pdf


