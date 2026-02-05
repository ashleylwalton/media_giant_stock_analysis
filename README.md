# Media Giant Stock Analysis (2019-Present) 
This project analyzes the long‑term performance, volatility, and industry dynamics of four major entertainment companies: **Disney (DIS), Comcast (CMCSA), Warner Bros Discovery (WBD), and Sony (SONY)**. The goal is to understand how different business models—theme parks, streaming, gaming, and diversified media assets—shape financial stability and long‑term returns.
The analysis includes exploratory data visualization, risk‑return evaluation, company‑level insights, and a final conclusion summarizing broader industry patterns


## Project Goals
- Compare long‑term stock performance across four entertainment giants
- Evaluate volatility, risk, and return characteristics
- Understand how business models (parks, streaming, gaming, broadband) influence financial behavior
- Identify which companies appear most stable or strongest over time
- Explore how diversification affects resilience during market shock


## Companies Analyzed
- Disney (DIS)
- Comcast (CMCSA)
- Warner Bros Discovery (WBD)
- Sony (SONY)


## Project Structure
projects/
    notebooks/
        media_giant_stock_analysis.ipynb
    outcomes/
    README.md
    requirements.txt


## Key Visuals
### Cumulative Returns
Shows how a $1 investment in each company grew over time, highlighting long‑term performance differences
![Cumulative Returns](outcomes/cumulative_returns.png)


### Risk vs. Return
Compares annualized returns with annualized volatility to show which companies offer better risk‑adjusted performance.
![Risk vs Return](outcomes/risk_vs_return.png)


## Key Findings
- The entertainment industry is highly sensitive to external shocks, especially for companies tied to theme parks and theatrical releases.
- Diversification is a major stabilizer: companies with gaming, broadband, or multiple media segments show smoother performance.
- Sony demonstrates the strongest long‑term stability, supported by recurring gaming revenue and globally recognized IP.
- Comcast shows steady performance due to broadband and Universal’s strong park recovery.
- Disney shows moderate volatility, driven by tourism cycles and streaming strategy shifts.
- Warner Bros Discovery is the most volatile, reflecting merger uncertainty and heavy reliance on streaming and linear TV.


## Methods and Analysis
The notebook includes:
### Exploratory Data Analysis
- Price history
- Cumulative returns
- Distribution of daily returns
- Correlation heatmap
### Risk & Return Analysis
- Annualized returns
- Annualized volatility
- Risk vs return scatterplot
- Summary table
### Company‑Level Insights
- COVID recovery patterns
- Streaming vs park‑heavy business models
- Diversification and volatility
- Long‑term performance comparison
### Conclusion
Summarizes what the data reveals about the entertainment industry, which companies appear strongest, and how business models shape financial outcomes


## How to Run This Project
- Clone the repository
- Install dependencies (optional: use requirements.txt)
- Open the notebook in Jupyter or VS Code
- Run all cells from top to bottom


## Future Work
- Add valuation metrics (P/E, price‑to‑sales, free cash flow)
- Compare streaming subscriber trends with stock performance
- Analyze major film releases and their short‑term market impact
- Expand the dataset to include Netflix, Apple, or other tech‑entertainment hybrids
- Build a simple portfolio optimization model using these four companies

