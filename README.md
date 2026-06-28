# 🎰 High-Volatility Slot Machine Analysis – 8 Lines, 3 Reels, 30 Symbols

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## 📋 Overview

Comprehensive mathematical and statistical analysis of a **high-volatility** slot machine with **3 reels**, **30 symbols**, and **8 paylines**.

**Key Specs:**
- 3 reels × 30 symbols = 27,000 combinations
- 5 special symbols (1-5) return the bet when in middle position
- Paytable: 2 matches → 1.5×, 3 matches → 590×
- 8 paylines across a 3×3 grid

**Methodologies:** Monte Carlo Simulation, RTP Analysis, VaR, Bayesian Inference

---

## 📊 Key Results

| Metric | Result | Status |
|--------|--------|--------|
| **RTP** | 95.274% | ✅ Target 95% |
| **Volatility (CV)** | 7.37 | ✅ High |
| **Hit Rate** | 72.95% | ✅ High engagement |
| **3-Match (per line)** | 0.1114% (1 in 897) | ✅ Matches theory (1 in 900) |
| **3-Match (per spin)** | 0.8913% (1 in 112) | ✅ Matches theory (1 in 112.5) |
| **Max Win** | 1,777.5× | ✅ High thrill potential |
| **VaR (95%)** | 0 credits | ✅ Low risk |

**18/82 weight distribution** – High-Risk (30 × 590 = 17,700) / Low-Risk (2,610 × 1.5 = 3,915)

---

## 📊 Low vs High Volatility Comparison

| Metric | Low Volatility (72/28) | High Volatility (18/82) |
|--------|------------------------|-------------------------|
| **3-Match Payout** | 200× | 590× |
| **2-Match Payout** | 6× | 1.5× |
| **RTP** | 95.188% | 95.274% |
| **Hit Rate** | 72.92% | 72.95% |
| **Volatility (CV)** | 2.61 | 7.37 |
| **Max Win** | 806× | 1,777.5× |

---

## 🛠️ Tech Stack

`Python` · `NumPy` · `SciPy` · `Matplotlib` · `Jupyter`

## 📁 Files

- `casino_slot_simulation_high_volatility.ipynb` – Main analysis notebook
- `casino_slot_simulation_low_volatility.ipynb` – Low volatility version
- `requirements.txt` – Dependencies

## 🚀 Run It

```bash
pip install numpy scipy matplotlib jupyter
jupyter notebook casino_slot_simulation_high_volatility.ipynb
