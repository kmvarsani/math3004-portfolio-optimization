# math3004-portfolio-optimization
MATH3004 Industrial Project — Smart Investment Portfolio Architect (Weeks 1–8)

# Smart Investment Portfolio Architect  
**MATH3004 Industrial Project — Semester 2, 2025**  
**Author:** Krish Varsani  

---

## 📘 Project Overview
This project develops a **simulation-based portfolio optimisation framework** that integrates:
- Conditional Value-at-Risk (CVaR) optimisation  
- Machine-learning-based regime detection  
- Bootstrap validation and scenario analysis  
- Interactive and explainable visual outputs  

The goal is to design a **robust, adaptive investment strategy** that outperforms benchmark portfolios such as the S&P 500, under realistic market and transaction constraints.

---

## 🧩 Repository Structure
math3004-portfolio-optimization/

- Week1–8.ipynb # Weekly Jupyter Notebooks
 
- figures # Generated visualisations

- data # Parquet, NumPy, and model files

- requirements.txt # Python dependencies

- README.md # Project documentation


---

## 🔬 Weekly Progress
| Week | Focus | Outputs |
|------|--------|----------|
| 1 | Simulation & data setup | Synthetic asset paths |
| 2 | Feature engineering | Feature parquet, statistics |
| 3 | Scenario modelling | Scenario cube, horizon analysis |
| 4 | CVaR optimisation | Frontier, ECDF, weights |
| 5 | Regime classification | Reliability & ROC plots |
| 6 | Backtesting | Equity curves, weights timeline |
| 7 | Bootstrap & explainability | KPI violin plots, feature importance |
| 8 | Final analysis | Drawdowns, KDE, sensitivity metrics |

---

## 🧠 Methodology
The workflow integrates:
1. **Scenario generation** via Monte Carlo simulation  
2. **Regime identification** using LightGBM classification  
3. **CVaR-based optimisation** to minimise downside tail risk  
4. **Bootstrap resampling** for performance robustness  
5. **Explainability analysis** using feature importance and partial dependence plots  

---

## 📈 Key Figures
- Week 4 — Efficient frontier, ECDF, and weight composition  
- Week 5 — Reliability curve and ROC-AUC  
- Week 6 – 7 — Equity curves and adaptive weight timelines  
- Week 8 — Drawdown and KDE distribution  

---

## ⚙️ Reproducibility
To recreate results locally:
```bash
pip install -r requirements.txt
jupyter notebook Week6.ipynb
