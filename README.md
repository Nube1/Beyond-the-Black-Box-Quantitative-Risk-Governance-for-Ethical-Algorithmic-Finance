# 📊 Beyond the Black Box: Quantitative Risk Governance for Ethical Algorithmic Finance

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

This repository contains the **Quantitative Risk Governance Framework (QRGF)** and the companion computational notebook for the research chapter: *"Beyond the Black Box: A Quantitative Risk Governance Framework for Ethical Algorithmic Finance in Emerging Markets."*

## 📖 Overview

In emerging markets (Sub-Saharan Africa, Latin America, Southeast Asia), fintechs use **alternative data** to score the unbanked. However, these "black box" models often scale historical prejudices with mathematical efficiency. 

This project introduces **Architectural Justice**—a shift from post-hoc "patches" to a proactive, structural governance of AI in finance.

### Key Research Contributions
1.  **Double Discrimination Phenomenon:** Mathematical proof of how feature sparsity in the Global South leads to systemic credit rejection.
2.  **SHAP/LIME Instability Analysis:** Empirical evidence that common "explainability" tools are unstable across random seeds.
3.  **The Portability Trap:** Analysis of why Western fairness metrics (Equalized Odds, etc.) fail in informal economies.
4.  **The QRGF:** A 5-pillar framework fusing **SR 11-7 Model Risk Management** with the **NIST AI RMF**.

---

## 💻 Companion Computational Notebook

The core of this repository is a reproducible analysis mapping directly to the book chapter.

| Notebook Section | Chapter Section | Core Hypothesis |
|---|---|---|
| **§1 Setup** | — | Environment, dependencies, and synthetic data generation. |
| **§2 Double Discrimination** | §1.3.2 | Sparse digital footprints generate measurable bias (Stage 1 & 2). |
| **§3 SHAP Instability** | §1.4.2 | SHAP attributions are unstable across random seeds in credit models. |
| **§4 Portability Trap** | §1.3.3 | Western fairness metrics misfire in emerging markets; Contextual Parity is needed. |
| **§5 Manipulation-Proof** | §1.5.4 | Transparent, manipulation-proof models outperform opaque ones via cost-taxonomies. |
| **§6 ERI Dashboard** | §1.5.5 | **Ethical Risk Indicators (ERIs)** detect algorithmic drift and bias in real time. |
| **§7 QRGF Audit** | §1.5 | Full framework checklist and "Pass/Fail" report card for AI models. |

---

## 🏛 The QRGF Pillars
The framework is built on five pillars of **Architectural Justice**:
1.  **Epistemic Transparency:** Counterfactual explanations over unstable heatmaps.
2.  **Corrective Equity:** Context-aware fairness metrics (CFAP).
3.  **Procedural Robustness:** Manipulation-proof feature weighting.
4.  **Precautionary Governance:** Real-time Ethical Risk Indicators (ERIs).
5.  **Structural Resilience:** Federated learning and Differential Privacy.

---

## 🚀 Getting Started

### Prerequisites
* Python 3.9 or higher
* `pip install xgboost shap lime scikit-learn pandas numpy matplotlib seaborn`

### Installation
```bash
git clone https://github.com/your-username/beyond-the-black-box.git
cd beyond-the-black-box
pip install -r requirements.txt
```

### Running the Simulations
Open the `QRGF_Framework_Analysis.ipynb` in Jupyter or upload it to Google Colab to replicate the **Double Discrimination** plots and **ERI Dashboard** simulations.

---

## 🌍 Case Studies Included
The notebook and paper provide calibration data for:
*   🇧🇷 **Brazil:** Central Bank (BCB) Anomaly Scoring.
*   🇿🇦 **South Africa:** Redressing structural exclusion under POPIA.
*   🇮🇳 **India:** The "Account Aggregator" Public Good Stack.
*   🇨🇳 **China:** Hard-law accountability for fintech giants.
*   🇮🇩 **Indonesia:** SupTech monitoring for P2P lending.
*   🇰🇪 **Kenya:** Healthcare and Insurtech algorithmic governance.

---

## 📝 Citation
If you use this framework or code in your research, please cite:

> Mahomane, R., & Mahlangu, J. (2026). *Beyond the Black Box: A Quantitative Risk Governance Framework for Ethical Algorithmic Finance in Emerging Markets.* [Institution/Publisher].

---

## ⚖️ License
Distributed under the **MIT License**. See `LICENSE` for more information.

**Contact:** [Ronald Mahomane) 
