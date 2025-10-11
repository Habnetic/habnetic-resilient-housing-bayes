# Resilient Housing Bayes

Bayesian simulation framework exploring how housing systems respond to stochastic climate events.  
Includes synthetic data generation, probabilistic fragility modeling, and estimation of downtime and reconstruction cost for resilience assessment.

---

## 1. Purpose

This repository is a learning and research environment to:
- Practice Bayesian modeling with realistic yet synthetic data.
- Explore resilience concepts in the built environment.
- Demonstrate open, reproducible computational workflows for architectural and urban systems.

No proprietary data or job-related materials are included.

---

## 2. Project structure

```
resilient-housing-bayes/
│
├── data/
│   └── synthetic/                  # generated storm and building datasets
│
├── notebooks/
│   ├── 01_simulate_storms.ipynb    # Monte Carlo climate events
│   ├── 02_fragility_and_failure.ipynb
│   ├── 03_bayesian_downtime_model.ipynb
│   └── 04_visualization_and_reporting.ipynb
│
├── reports/
│   └── 2025-10-11_project-plan.md
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 3. Methods (conceptual)

1. **Monte Carlo storm generation** — random sampling of event intensity, duration, and frequency.  
2. **Fragility modeling** — probability of component failure given event intensity.  
3. **Bayesian inference** — hierarchical model estimating building downtime and reconstruction cost with uncertainty bounds.  
4. **Posterior analysis** — credible intervals, expected loss, and sensitivity to priors.

---

## 4. Learning goals

- Understand hierarchical Bayesian modeling.  
- Build and evaluate synthetic datasets for uncertainty analysis.  
- Communicate probabilistic results clearly through plots and summaries.  

---

## 5. Dependencies

Install requirements (Python ≥3.10):

```bash
pip install -r requirements.txt
```

Typical stack:
- numpy, pandas, matplotlib, arviz
- pymc or stan
- jupyter or colab

---

## 6. Usage

Clone the repository and open the notebooks sequentially:

```bash
git clone https://github.com/mikel-knwoledge/resilient-housing-bayes.git
cd resilient-housing-bayes/notebooks
jupyter notebook
```

Each notebook is standalone and documented.

---

## 7. License

MIT License — open for learning, teaching, and research reuse.

---

## 8. Author

Mikel — Architect and digital strategist  
Focused on Bayesian reasoning for design resilience and computational learning.
