# Equity-default-risk-analysis
Default risk assessment. Analyzes equity value trajectories under various market scenarios including stress testing with 2008 financial crisis parameters. 
Implements traffic light decision framework for investment recommendations.  
Tech: Excel | Topics: Risk Management, Scenario Analysis

## Overview
This project analyzes the default risk of a £600M commercial real estate investment by evaluating equity value trajectories over a 10-year period and the impact of interest rate swaps on investment viability.

## Project Details
### Investment Structure
- **Purchase Price**: £600,000,000
- **Debt Financing**: £400,000,000 (66.67%)
- **Equity Investment**: £200,000,000 (33.33%)
- **Gross Rental Yield**: 3.6%
- **Loan Term**: 10 years

### Analysis Components
#### 1. Base Case Scenario
- **Capital Gains**: 2% annually
- **Interest Rate**: LIBOR GBP + 50 basis points
- **Result**: Equity value remains positive throughout 10-year period
- **Final Equity Value (2025)**: £295.5M

#### 2. Worst-Case Stress Test
- **Capital Gains**: -8% annually (2008 crisis level)
- **Interest Rate**: 0.0255% (2020 historical low)
- **Result**: Equity becomes negative in Year 9 (2024)
- **2024 Equity**: -£11.9M
- **2025 Equity**: -£24.1M

### Interest Rate Swap Analysis
- Comparison of floating LIBOR vs fixed rate (LIBOR + 30bps)
- Swap valuation calculations showing impact on equity position
- Analysis demonstrates that rising LIBOR rates benefit the fixed-rate position

## Key Findings
1. Investment remains viable under normal market conditions
2. Property value appreciation is critical to maintaining positive equity
3. Stress scenario reveals need for collateral arrangements by Year 9
4. Interest rate hedging through swaps provides protection in rising rate environment

## Technical Implementation
- **Tool**: Microsoft Excel with advanced financial modeling
- **Key Features**:
  - Dynamic scenario analysis
  - Present value calculations for swap valuation
  - 10-year cash flow projections
  - Sensitivity analysis on key parameters

## File Structure
## Model Outputs
- Annual equity value progression
- Swap value calculations
- Property value projections
- Debt amortization schedule

## Investment Recommendation
**Status: AMBER** ⚠️
- Proceed with investment but implement risk mitigation:
  - Negotiate swap spread reduction (target: 20-30 bps)
  - Establish collateral facility for stress scenarios
  - Monitor property market conditions quarterly

## How to Use
1. Open `Equity Default Risk Analysis.xlsx`
2. Base case analysis is in rows 1-28
3. Worst-case scenario begins at row 31
4. Modify parameters in cells B2-B10 for sensitivity analysis

## Assumptions & Limitations
- Constant rental yield assumption
- No consideration of refinancing options
- Property transaction costs not included
- Exchange rate risk for CHF portion not fully modeled

## Author
Sita-Fatime Dosso  
Master of Financial Economics, Western University  
[LinkedIn](https://www.linkedin.com/in/fatimedosso/) | sdosso@uwo.ca

*Note: This academic project demonstrates commercial real estate risk analysis methodology. Actual investment decisions require comprehensive due diligence and professional advice.*
