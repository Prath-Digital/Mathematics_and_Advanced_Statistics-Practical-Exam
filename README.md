# 📘 Mathematics & Advanced Statistics Practical Exam

Welcome! This repository contains the complete submission for the **Mathematics & Advanced Statistics Practical Exam** (theory + Python practical) using the generated dataset `employee_performance.csv`.

---

## 🎯 Project Overview
This exam is divided into two parts:

- **Part A — Theory:** Short-answer questions on fundamental statistics concepts.
- **Part B — Practical (Python):** A Jupyter notebook analysis using the generated dataset.

The goal is to demonstrate clear explanations (Part A) and reproducible Python analysis (Part B).

---

## 📁 Repository Structure
```
├── analysis.ipynb          # Python notebook with Part B analysis
├── report.html             # Rendered HTML report of analysis
├── report.pdf              # Printable PDF report of analysis
├── LICENSE                 # License details
└── README.md               # This file
```

---

## 🧪 What’s Included (Task Coverage)
### ✅ Part A — Theory (Short Questions)
The notebook/report includes short explanations for:
- Mean / Median / Mode (with workplace salary context)
- Range vs Variance
- Normal vs Poisson distributions
- Skewness (with a workplace example)
- Conditional probability (promotion context)
- Independent vs mutually exclusive events
- Bayes’ theorem and decision-making
- PCA (Principal Component Analysis) in simple terms

### 🧠 Part B — Practical (Python Programming)
The analysis notebook covers:
1. **Central Tendency & Dispersion**
   - Mean, median, mode of salary
   - Variance + standard deviation of projects completed
2. **Probability & Events**
   - Probability of promotion
   - Contingency table (Promotion_Status vs Department)
   - Conditional probability: P(Promotion | Performance_Score > 80)
3. **Distributions & Visualization**
   - Histogram + Gaussian curve of Performance_Score
   - Skewness and kurtosis for Salary
   - Q-Q plot for Projects_Completed
4. **Linear Algebra Application**
   - Dot product between employee vectors
   - Norm calculation (vector length)
   - Angle between two employee work vectors

---

## 📌 Key Results (Dataset Snapshot)
These values are computed from the current `employee_performance.csv` dataset using the analysis notebook.

- **Salary (₹)**
  - Mean: **59,944.64**
  - Median: **59,587.50**
  - Mode: **64,135**
- **Projects_Completed**
  - Variance: **29.83**
  - Standard deviation: **5.46**
- **Promotion Metrics**
  - Overall promotion probability: **39.4%**
  - Conditional probability (Performance_Score > 80): **100%**
- **Distribution insights**
  - Salary skewness: **0.004** (≈ symmetric)
  - Salary kurtosis: **-1.22** (light tails)

---

## ▶️ Run the Analysis
### 0) Clone the repository
```bash
git clone https://github.com/Prath-Digital/Mathematics_and_Advanced_Statistics-Practical-Exam.git
cd Mathematics_and_Advanced_Statistics-Practical-Exam
```

### 1) Install dependencies (recommended via `pip`)
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### 2) Open the notebook
```bash
jupyter notebook analysis.ipynb
```

### 3) (Optional) Export reports
```bash
jupyter nbconvert --to html analysis.ipynb --output report.html
jupyter nbconvert --to pdf analysis.ipynb --output report.pdf
```

---

## 📬 Contact
- **Author:** Prath Udhnawala
- **Email:** askforvarn@gmail.com

---

## 📝 License
This project is released under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 📌 Notes
- The dataset is synthetic and generated to match exam requirements.
- `report.html` and `report.pdf` contain exported results and screenshots for easy review.

---

Good luck reviewing — and happy analytics! 🚀
