# Asset Allocation with a Carbon Objective

This project explores sustainable investment strategies by implementing various portfolio optimization techniques with a focus on carbon emissions reduction. The analysis spans from 2006 to 2022, examining different portfolio construction approaches that balance financial performance with environmental considerations.

## Project Overview

The project is divided into three main parts:

1. **Standard Asset Allocation**
   - Implementation of rolling window optimization
   - Benchmark comparison with value-weighted portfolio
   - Analysis of portfolio performance metrics

2. **Asset Allocation with Carbon Emissions Reduction**
   - WACI (Weighted Average Carbon Intensity) and CF (Carbon Footprint) calculations
   - Long-only MVP portfolio with Carbon Footprint constraints
   - Tracking Error optimization relative to Value Weighted Portfolio
   - Analysis of trade-offs between financial performance and carbon reduction

3. **Allocation with Net Zero Objective**
   - Implementation of Net Zero Portfolio strategy
   - Performance comparison with other portfolio versions
   - Analysis of sustainability metrics

## Key Features

- **Data Preprocessing**: Comprehensive cleaning and filtering of stock data, focusing on high-polluting sectors (Energy, Materials, Utilities, and Industrials)
- **Multiple Portfolio Strategies**:
  - Minimum Variance Portfolio (MVP)
  - Carbon-Constrained MVP
  - Tracking Error Optimization
  - Net Zero Portfolio
- **Carbon Metrics Implementation**:
  - WACI calculations
  - Carbon Footprint analysis
  - Scope 1, 2, and 3 emissions consideration

## Results Highlights

- The optimized portfolios consistently outperform the value-weighted benchmark
- Carbon-constrained portfolios achieve competitive returns while reducing environmental impact
- Net Zero Portfolio demonstrates the viability of combining financial and sustainability objectives

## Key Performance Metrics

| Portfolio Type | Annualized Return | Volatility | Sharpe Ratio | Max Drawdown |
|----------------|------------------|------------|--------------|--------------|
| MVP            | 9.66%           | 11.30%     | 0.85         | -25.12%      |
| Value-Weighted | 7.72%           | 18.01%     | 0.43         | -52.16%      |
| Net Zero       | 9.49%           | 18.09%     | 0.52         | -52.61%      |

## Methodology

- **Rolling Window Optimization**: 6-year windows from 2005 to 2022
- **Carbon Constraints**: Implementation of 50% carbon footprint reduction target
- **Performance Assessment**: Analysis of returns, volatility, Sharpe ratios, and maximum drawdowns

## Conclusions

1. MVP portfolios demonstrate superior risk-adjusted returns compared to benchmark
2. Carbon constraints can be implemented without significant performance sacrifice
3. Net Zero objectives are achievable while maintaining competitive financial performance

## Technical Requirements

- Python for data analysis and portfolio optimization
- Financial data processing capabilities
- Carbon emissions data integration
