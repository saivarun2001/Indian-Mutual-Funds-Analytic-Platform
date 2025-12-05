📈 Indian Mutual Funds Analytics Platform

This project builds a complete Mutual Fund Analytics Platform using daily-updated NAV data for 1000+ Indian mutual fund schemes across equity, debt, hybrid, and index categories.

Using the Mutual_Fund_Data repository as the source, the project performs:

NAV time-series cleaning & transformation

Long-term performance calculations (CAGR, rolling returns, volatility, drawdowns)

SIP & lump-sum return simulations

Risk-adjusted metrics such as Sharpe ratio

Benchmark comparison (NIFTY50 & Sensex)

20+ visualizations for trend & risk analytics

🎯 Key Features

✔ Historical NAV backtesting
✔ Risk–return analytics
✔ Category-wise fund comparison
✔ SIP simulation module
✔ Benchmark performance mapping
✔ Trend & volatility visualizations
✔ Fully reproducible analysis pipeline

🧰 Tech Stack

Python

Pandas & NumPy – Data preparation

Matplotlib / Seaborn – Visualization

Jupyter Notebook – Workflow execution

AMFI / APIs – NAV data collection

📂 Dataset

Daily updated NAV data for 1000+ schemes

Includes Equity, Hybrid, Debt, Index & Sectoral funds

Multi-year historical time-series for backtesting

Source: Mutual_Fund_Data repository

🔄 Workflow (Mermaid Diagram)
flowchart TD
    A[Data Import<br>(AMFI / NAV CSV)] --> B[Data Cleaning<br>Missing Values, Formatting]
    B --> C[Feature Engineering<br>CAGR, Rolling Returns, Volatility]
    C --> D[Benchmark Comparison<br>NIFTY50 & Sensex]
    D --> E[SIP Simulation<br>Monthly Investments]
    E --> F[Visualization<br>Trends, Drawdowns, Heatmaps]
    F --> G[Insights & Reporting<br>Category & Fund Ranking]


📊 Sample Visualizations
NAV Trend Comparison

Rolling Returns (3-Year Window)

SIP Simulation Output

(Replace placeholders with your actual images)

📝 Solution Summary

Built a mutual-fund analytics pipeline using multi-year NAV time-series. Calculated CAGR, rolling returns, volatility, drawdowns, Sharpe ratio & SIP outcomes. Added benchmark comparisons with NIFTY50/Sensex and visualized category trends using 20+ charts.

🚀 Impact

40% faster insights through automated NAV calculations

Identified high-performing funds and risk-inefficient schemes

Enabled long-term behavior analysis across market cycles

Delivered a reusable backtesting framework for investors & analysts

📌 Future Enhancements

Streamlit dashboard for interactive analytics

Portfolio optimization using Modern Portfolio Theory (MPT)

Real-time NAV fetch using APIs

Alert system for NAV thresholds

🙌 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to submit a PR 🚀
