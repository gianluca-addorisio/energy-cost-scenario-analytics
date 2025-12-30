# Energy Cost Scenario Analytics
Scenario-based energy cost and risk analytics for corporate decision-making.

This repository develops a transparent and reproducible framework to translate
energy price uncertainty into cost and risk metrics for energy-exposed firms.

The project is designed for decision support, not for price forecasting or trading.

---

## What this project does

- Constructs **structured energy price stress scenarios**
- Maps scenarios into **cost trajectories** using a transparent cost model
- Quantifies **downside cost risk** relative to a planning baseline
- Produces interpretable **risk metrics** for budgeting and stress testing

The focus is on usability, interpretability, and decision relevance rather than
black-box models or point forecasts.

---

## Methodological structure

The analysis is organized into modular notebooks:

- `notebooks/00_project_overview.ipynb`  
  Conceptual overview, objectives, and decision context.

- `notebooks/01_data_pipeline.ipynb`  
  Data ingestion, cleaning, and preprocessing of historical energy prices.

- `notebooks/02_scenarios.ipynb`  
  Construction and visualization of exogenous stress scenarios.

- `notebooks/03_cost_impact_model.ipynb`  
  Mapping of energy price scenarios into cost paths using a parametric cost function.  
  Outputs include full scenario cost trajectories and a baseline planning cost.

- `notebooks/04_risk_metrics.ipynb`  
  Development of decision-oriented risk metrics, including:
  - Percentile-based cost overruns
  - Worst-case cumulative cost exposure
  - Cost-at-Risk (CaR) over a finite planning horizon

---

## Decision framework

- **Perspective:** Energy-exposed firm (planning / budgeting / risk management)
- **Baseline:** Deterministic planning scenario (business-as-usual)
- **Horizon:** Short- to medium-term (e.g. 6 months)
- **Outputs:** Monetary cost deviations relative to baseline

All major structural choices are documented through explicit Decision Records.

---

## Intended use

This project is designed for:
- corporate analytics and decision-support teams,
- risk management and scenario analysis functions,
- planning, budgeting, and strategy roles.

It is **not** intended as a trading, forecasting, or high-frequency modeling system.

---

## Project status

- Version 1 completed and versioned
- Pipeline structurally complete and reproducible
- Ongoing work focuses on refining the planning baseline and extending risk metrics (V2)

