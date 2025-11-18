# Global Supply Chain Cost Optimization

Optimization of a global supply chain network to minimize total costs while balancing tariffs, transportation, production, and exchange rate effects.

## 1. Overview

This project analyzes and optimizes a global supply chain network for a manufacturing company operating across multiple regions. The goal is to determine cost-effective production and distribution strategies that minimize total logistics and tariff costs while meeting customer demand.

The work reflects a realistic business scenario where companies must decide:
- Where to produce,
- How much to ship between facilities and markets,
- And how to adapt to changes in tariffs, transportation costs, and exchange rates.

## 2. Data

The dataset includes:
- Production capacities by plant
- Demand by region/market
- Transportation costs between plants and markets
- Tariffs and trade costs between regions
- Exchange rate information

All data is structured to support network optimization and scenario analysis.

## 3. Approach

The analysis follows these main steps:

1. **Data understanding & preprocessing** – Load and clean supply chain input tables (capacities, costs, demand, tariffs).
2. **Baseline cost calculation** – Compute current cost structure for existing production and distribution flows.
3. **Optimization model** – Formulate a cost-minimization problem with:
   - Decision variables: production quantities and shipment quantities.
   - Objective function: minimize total cost (production + transportation + tariffs).
   - Constraints: capacity limits, demand satisfaction, and flow balance.
4. **Scenario analysis** – Evaluate how changes in tariffs or exchange rates affect the optimal network design and total cost.

The analysis is implemented in a Jupyter Notebook:  
- `SC Management.ipynb`

## 4. Methods & Techniques

- Linear / network optimization modeling
- Scenario analysis and sensitivity analysis
- Cost decomposition and comparison of baseline vs. optimized scenarios

## 5. Results & Insights

Key insights from the optimization include:

- Identification of **optimal production locations** that balance low manufacturing cost and proximity to demand.
- Recommendations on **which routes to prioritize** for shipping to reduce transportation and tariff costs.
- Quantified **cost savings** by comparing the optimized solution against the baseline network.
- Understanding of how **tariff changes and exchange rate fluctuations** influence the best production and distribution strategy.

These results can support strategic decisions on:
- Plant utilization,
- Regional sourcing strategy,
- Long-term supply chain design.

## 6. Tools & Technologies

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** 
  - `pandas`, `numpy` for data handling
  - Optimization libraries (e.g., `PuLP` or similar, depending on implementation)
- **Visualization:** Basic plots and tables in the notebook

## 7. Repository Structure

- `SC Management.ipynb` – Main notebook with data analysis and optimization model  
- `Global Supply Chain Optimization Presentation.pdf` – Slide deck summarizing the problem, approach, and results  
- `Supply Chain Optimization Report.pdf` – Detailed report with findings and recommendations  

## 8. How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ShemezaDonald/Global-supply-chain-cost-optimization.git
   cd Global-supply-chain-cost-optimization

