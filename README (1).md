
# 🧠 Entropy-Constrained Structure in the Riemann Zeta Zeros

This repository contains the code, data processing, and visualizations used in the empirical analysis for the paper:

> **Entropy-Constrained Structure in the Riemann Zeta Zeros**  
> ✍️ *Joshua Jesuraj Sanctus*  
> 📄 Submitted to *Global Philosophy (formerly Axiomathes)*  
> 📧 Contact: jjesuraj37@gmail.com

---

## 🧠 Project Overview

This project investigates whether the nontrivial zeros of the Riemann zeta function exhibit **minimal Shannon entropy** in their spacing distribution — supporting the hypothesis that the Riemann Hypothesis (RH) reflects a structural constraint on **symbolic compressibility** and **information economy**.

Using high-precision datasets of Riemann zeros (Odlyzko’s tables), this repository provides:

- 🔢 Spacing distribution and KDE analysis  
- 📉 Entropy computation and perturbation modeling  
- 🔁 Symbolic reconstruction of the Chebyshev prime-counting function ψ(x)  
- 📊 Visualizations of entropy growth and prime recovery

---

## 📁 Folder Structure

```
.
├── zero.csv                # Input file: high-precision Riemann zeros
├── entropy_analysis.py     # Entropy & perturbation script
├── prime_reconstruction.py # Prime estimation using zeros (ψ-reconstruction)
├── figures/                # Output graphs and KDE plots
├── results/                # CSV/txt logs of entropy & reconstruction
└── README.md               # This file
```

---

## 🧪 Requirements

- Python 3.8+  
- Install dependencies:

```bash
pip install numpy pandas matplotlib scipy sympy
```

---

## 🚀 How to Run

### 1. 🔄 Entropy & Perturbation Modeling

```bash
python entropy_analysis.py
```

Performs entropy computation under perturbation strengths (ε), generating:

- Spacing histograms and KDE plots  
- Entropy growth curves: `figures/entropy_vs_sigma.png`

---

### 2. 🔢 Prime Reconstruction from Zeros

```bash
python prime_reconstruction.py
```

- Estimates ψ(x) using the first 10,000 zeros  
- Detects prime jumps in ψ(x)  
- Compares predicted vs. true primes (x ≤ 100)

---

## 📊 Sample Outputs

- `figures/output1.2.png` — Spacing histogram (ε = 0.0)  
- `figures/output1.4.png` — Spacing histogram (ε = 1.0)  
- `figures/entropy_vs_sigma.png` — Entropy curve vs. perturbation  
- `figures/psi_reconstruction.png` — Reconstructed ψ(x) and primes

---

## 📚 Citations

If you use this code, please cite:

```bibtex
@misc{sanctus2025entropy,
  author = {Joshua Jesuraj Sanctus},
  title = {Entropy-Constrained Structure in the Riemann Zeta Zeros},
  journal = {Global Philosophy (under review)},
  year = {2025},
  url = {https://github.com/YOUR-REPO}
}
```

### Relevant References

- Odlyzko, A.M. (1992). *The $10^{20}$-th Zero of the Riemann Zeta Function*  
- Shannon, C.E. (1948). *A Mathematical Theory of Communication*  
- Edwards, H.M. (1974). *Riemann's Zeta Function*. Academic Press.

---

## 🧠 License

This repository is shared for academic and research purposes.  
All original content © 2025 *Joshua Jesuraj Sanctus*.

---

## 🧭 Philosophy–Math Boundary Statement

This project bridges **formal mathematical structure** with **philosophical interpretation**. Entropy analysis is not presented as proof of RH, but as empirical evidence for a **compressibility constraint** governing arithmetic structure.

---
