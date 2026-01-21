# Stratify-Inventory_Rewired
A supply chain analytics tool that optimizes inventory replenishment using multi-model forecasting and stochastic simulation to maximize service levels and minimize costs.

This is a Python-based inventory optimization framework designed to bridge the gap between static inventory policies and dynamic real-world demand. It utilizes statistical forecasting and stochastic simulation to minimize stockouts while optimizing holding costs.

Key Features
Intelligent Demand Forecasting: Automatically selects the best model based on data characteristics (CV, seasonality):

Holt-Winters for seasonal data.

Croston’s Method for intermittent/lumpy demand.

Exponential Smoothing for trend-based data.

Inventory Optimization: Dynamic calculation of EOQ (Economic Order Quantity), Safety Stock, and Reorder Points (ROP) that accounts for supplier lead-time variability.

Risk-Aware Simulation: Runs 21-day (configurable) simulations to stress-test inventory policies against supplier delays and demand shocks.

Performance Analytics: Generates comprehensive dashboards for KPIs like Fill Rate, Service Level, Inventory Turnover, and Cost Breakdown.
