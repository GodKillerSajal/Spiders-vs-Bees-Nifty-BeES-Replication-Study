# Spiders vs. Bees: A Replication Study of Nifty BeES

**Context & Affiliation**: Financial Economics Research Project | Supervised by Prof. Manish Kumar Singh, IIT Roorkee  
**Domain**: Empirical Asset Pricing, Market Microstructure, ETF Pricing Efficiency & Tracking Error  
**Research Paper**: *ETFs in India: Where Are the Bugs? A Replication Study of Nifty BeES* (Replication and adaptation of the seminal Elton, Gruber, Comer, and Li (2002) SPDR / "Spiders" framework for the Indian market).  
**Data Horizon**: 2013 to 2021 historical Net Asset Value (NAV), market trade prices, and Nifty 50 Total Returns Index (TRI).

---

## 1. Research Objectives
To evaluate the pricing efficiency, tracking quality, and market microstructure mechanics of India's flagship Exchange-Traded Fund (Nippon India Nifty 50 BeES), measuring return differentials against the benchmark index, analyzing the persistence of Price-to-NAV deviations, and quantifying the "value of immediacy" (liquidity premium).

---

## 2. Econometric & Analytical Framework
- **Annualized Return Decomposition**: Disentangled total ETF performance relative to the Nifty 50 Total Returns Index (TRI) into true tracking error (price index replication error) and residual components (expense drag vs. dividend reinvestment timing).
- **Price-NAV Deviation & Mean-Reversion Modeling**: Formulated autoregressive time-series regressions ($\Delta \text{Dev}_t = \alpha + \beta \text{Dev}_{t-1} + \epsilon_t$) to test the speed and magnitude of arbitrage correction by Authorized Participants (APs).
- **Comparative Investment Vehicle Analysis**: Evaluated Nifty BeES performance and expense efficiency relative to open-ended index mutual funds and Nifty index futures.
- **Microstructure & Trading Volume Determinants**: Modeled the impact of market volatility (India VIX) and premium/discount spreads on intraday ETF trading turnover.

---

## 3. Key Empirical Findings
- **Exceptionally Tight Tracking**: Total annualized NAV underperformance vs. Nifty TRI was only **$-0.53\text{ bps}$** (tracking error of $-1.20\text{ bps}$ offset by $+0.66\text{ bps}$ residual cash/dividend accrual).
- **Rapid Arbitrage Correction ($R^2 \approx 0.40$)**: Found that nearly $40\%$ of next-day variation in price deviations is absorbed through creation/redemption arbitrage, preventing prolonged mispricing.
- **Empirical Confirmation of Market Efficiency**: Demonstrated that Nifty BeES acts as an exceptionally cost-effective, liquid proxy for the Indian equity market with negligible tracking slippage.

---

## 4. Key Artifacts & Research Deliverables
- `Finance_Project_final.pdf`: Complete 10-page academic research paper detailing mathematical formulations, return decomposition tables, and econometric regressions.
- `finance__ppt.pdf`: 33-slide presentation deck prepared for the Department of Humanities and Social Sciences, IIT Roorkee.
