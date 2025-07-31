## Inventory Optimization using Monte Carlo Simulation

A Python-based project implementing Monte Carlo simulation techniques for inventory optimization under demand and lead time uncertainty.

## Overview

This project addresses the challenge of inventory management when facing stochastic demand and variable lead times. Traditional inventory models assume constant parameters, but real-world operations require robust solutions that account for uncertainty.

## Key Features

- **Monte Carlo Simulation**: Simulates stochastic demand and lead times across multiple scenarios
- **Risk Assessment**: Models stockout probabilities and safety stock requirements
- **Data Visualization**: Performance metrics and uncertainty impact visualization
- **Optimization**: Determines optimal reorder points, order quantities, and safety stock levels

## Methodology

The project simulates a multi-product retail environment with:

- Stochastic demand following various probability distributions
- Variable supplier lead times due to operational constraints
- Objective to minimize total costs while maintaining target service levels

Monte Carlo simulation generates thousands of scenarios to assess inventory performance under uncertainty and determine optimal inventory policies.

## Implementation

**Data Simulation**: NumPy and Pandas for generating stochastic scenarios  
**Monte Carlo Analysis**: Simulation of inventory cycles under uncertainty  
**Optimization**: Methods for determining optimal inventory parameters  
**Visualization**: Matplotlib charts for performance metrics and risk assessment

## Technologies

- **Python** - Core programming language
- **NumPy** - Numerical computations and random number generation
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **PuLP** - Linear programming optimization
- **Monte Carlo Simulation** - Risk modeling and uncertainty quantification

## Files

- `Supply Chain Optimization - Monte Carlo Simulation (Github).ipynb` - Main analysis notebook
- `data/` - Excel files containing demand, cost, and capacity data
- `README.md` - Project documentation
