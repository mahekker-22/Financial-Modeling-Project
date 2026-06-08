# Infosys Ltd. (NSE: INFY) — Institutional Equity Valuation & Financial Modeling Suite

A comprehensive corporate valuation and quantitative financial research suite evaluating **Infosys Limited**, a premier global information technology, consulting, and digital transformation enterprise.

> **Disclaimer:** These models and reports were created for academic and professional portfolio development purposes. The analysis relies on historical financial disclosures and assumptions constructed solely to demonstrate financial modeling proficiency. They do not constitute formal investment, legal, or financial advice.

## 📌 Project Overview
This repository aggregates a multi-layered financial modeling suite designed to assess the intrinsic value, capital structure efficiencies, operational performance, and credit stability of Infosys Ltd. The core modeling segments span historical ratio teardowns, automated valuation charts, and forward-looking projection matrices built entirely from fundamental data.

## 🛠️ Key Technical Sections & Financial Frameworks

### 1. Intrinsic Valuation: 5-Year Explicit DCF Model
* **FCFF Forecasting Engine:** Modeled forward-looking Free Cash Flow to Firm (FCFF) through FY2030 based on historical reinvestment rates, Return on Invested Capital (ROIC), and normalized operational cash flows.
* **WACC & Cost of Capital Calculation:** Formatted a granular Weighted Average Cost of Capital (WACC) matrix utilizing a peer-compositions unlevered/levered Beta framework, historical sovereign risk-free rates (6.72%), and long-term equity risk premiums.
* **Sensitivity Analysis & Terminal Value:** Structured an multi-variable lookup table testing intrinsic valuations against an intersecting range of WACC parameters and Gordon Growth Terminal Rates ($g = 7.4\%$), tracking target outputs up to a Base Case terminal valuation of **₹608,815.71 Cr**.
* **Scenario Modeling:** Programmed an interactive Scenario Summary switch testing distinct financial paths across **Base, Bull (Intrinsic: ₹1,291.01), and Bear (Intrinsic: ₹721.55)** operating conditions.

### 2. Relative Valuation: Comparable Company Analysis (CCA)
* **Trading Multiples Peer Group:** Evaluated trading dynamics against Indian IT services giants including Tata Consultancy Services (TCS), HCL Technologies, Wipro, and Tech Mahindra.
* **Valuation Multiples Derived:** Calculated real-time valuation markers including Enterprise Value-to-Revenue (EV/Rev), Enterprise Value-to-EBITDA (EV/EBITDA), and Price-to-Earnings (P/E) ratios.
* **Football Field Visualization Structuring:** Aggregated output boundaries across Comps, 52-week trading ranges, and DCF iterations into a standardized low-high data frame to map implied pricing bands seamlessly.

### 3. Quantitative Risk & Performance Diagnostics
* **Advanced Capital Asset Pricing (CAPM):** Plotted historical weekly returns against the benchmark NIFTY index to execute a **Beta Regression Analysis**, integrating raw levered beta tracking (0.78) alongside a standardized drifting mechanism.
* **DuPont Performance Teardown:** Deconstructed historic Return on Equity (ROE) and Return on Assets (ROA) profiles into asset turnover efficiency, structural profit margins, and financial leverage multipliers.
* **Altman’s Z-Score Bankruptcy Modeling:** Implemented a multi-stage distress warning model tracking working capital ratios, retained earnings growth, and market-cap leverage thresholds to assess long-term balance sheet durability.

## 📁 Repository Directory Structure
* `Infosys_DCF.xlsx` — Integrated 3-Statement financial model, regression beta tabs, intrinsic growth math, and scenario outputs.
* `Infosys_Comparable Company Analysis.xlsx` — Peer trading multiples valuation sheet and Football Field chart configurations.
* `Infosys_Historical FS ^0 Ratio analysis.xlsx` — Historical financial statements ledger, quarterly revenue trackers, and DuPont ratio scripts.

*Note: The underlying dynamic spreadsheet workbooks are preserved in view/data layouts to showcase operational architecture; all mathematical formulas, regression constants, and account cross-sections are fully preserved within the code-accessible CSV data maps.*
