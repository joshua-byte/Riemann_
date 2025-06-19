# Entropy-Constrained Structure in the Riemann Zeta Zeros

This repository contains the code, data processing, and visualizations used in the empirical analysis for the paper:

**"Entropy-Constrained Structure in the Riemann Zeta Zeros"**  
📄 Submitted to *Global Philosophy (formerly Axiomathes)*  
✍️ Author: Joshua Jesuraj Sanctus  
📧 Contact: jjesuraj37@gmail.com

## 🧠 Project Overview

This project investigates whether the nontrivial zeros of the Riemann zeta function exhibit minimal Shannon entropy in their spacing distribution, supporting the view that the Riemann Hypothesis reflects a structural constraint on symbolic compressibility and information economy.

Using high-precision datasets of Riemann zeros (Odlyzko's tables), the scripts perform:

- Spacing distribution analysis
- Entropy computation and perturbation modeling
- Symbolic reconstruction of prime-counting functions from zeros
- Visualization of spacing degradation and entropy curves

## 📁 Folder Structure

.
├── zero.csv # Input file containing Riemann zeta zeros
├── entropy_analysis.py # Main entropy computation and perturbation analysis
├── prime_reconstruction.py # Symbolic ψ(x)-based prime estimation from zeros
├── figures/ # Output plots and visualizations
├── results/ # CSV/txt logs of entropy and reconstruction data
└── README.md # This file

csharp
Copy
Edit

## 🧪 Requirements

Python 3.8+  
Install required packages with:

```bash
pip install numpy pandas matplotlib scipy sympy
🚀 How to Run
Entropy and Perturbation
bash
Copy
Edit
python entropy_analysis.py
Computes spacing entropy across various perturbation strengths (ε)

Generates plots of:

KDE spacing distributions

Entropy vs. perturbation level

Prime Reconstruction from Zeros
bash
Copy
Edit
python prime_reconstruction.py
Approximates ψ(x) using the first 10,000 zeros

Estimates prime locations via jump detection in ψ(x)

Compares predicted primes with true primes up to x ≈ 100

📊 Sample Output
figures/output1.2.png – Spacing histogram at ε = 0.0

figures/output1.4.png – Spacing histogram at ε = 1.0

figures/entropy_vs_sigma.png – Entropy growth under perturbation

figures/psi_reconstruction.png – ψ(x) curve and prime reconstruction

📚 Citations
If you use this code or dataset, please cite:

java
Copy
Edit
@misc{sanctus2025entropy,
  author = {Joshua Jesuraj Sanctus},
  title = {Entropy-Constrained Structure in the Riemann Zeta Zeros},
  journal = {Global Philosophy (under review)},
  year = {2025},
  url = {https://github.com/YOUR-REPO}
}
Also consider citing:

Odlyzko, A.M. (1992). The $10^{20}$-th zero of the Riemann zeta function.

Shannon, C.E. (1948). A Mathematical Theory of Communication.

Edwards, H.M. (1974). Riemann's Zeta Function. Academic Press.

🧠 License
This repository is shared for academic and research purposes. All original work © Joshua Jesuraj Sanctus.

yaml
Copy
Edit

---

Let me know if you want a badge-style header or GitHub Pages version.
