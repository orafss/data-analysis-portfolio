# Data Analysis Portfolio

A growing collection of Python data-analysis work — from core language fundamentals through to full exploratory analysis projects. Each notebook is self-contained and runnable.

**Author:** Franklyn Orafu · Aberdeen, Scotland
Chemical Engineering graduate (BEng, MSc Oil & Gas Engineering) building data-analysis skills alongside a process/HSE engineering background.

---

## Contents

| # | Notebook | Topic | Concepts covered |
|---|----------|-------|------------------|
| 01 | [`notebooks/01_python_sets.ipynb`](notebooks/01_python_sets.ipynb) | Python Sets | Set creation, mutation, set algebra (union/intersection/difference/symmetric difference), subset & superset tests, set & frozenset types, comprehensions, membership testing, iteration |

*More notebooks will be added as the portfolio grows.*

---

## Getting started

Clone the repo and launch Jupyter:

```bash
git clone https://github.com/<your-username>/data-analysis-portfolio.git
cd data-analysis-portfolio
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Then open any notebook under `notebooks/` and run the cells top to bottom.

---

## Repository structure

```
data-analysis-portfolio/
├── notebooks/          # Jupyter notebooks, one per topic/assignment
├── requirements.txt    # Python dependencies
├── .gitignore
├── LICENSE
└── README.md
```

---

## Tech

- Python 3.12+
- Jupyter Lab / Notebook

## License

Released under the MIT License — see [`LICENSE`](LICENSE).
