
# MScFE Capstone Group 9192

Welcome to the official repository for the MSc Financial Engineering Capstone Project by Group 9192.

## 📘 Project Overview

**Project Title:**  
**Asset Allocation and Machine (Deep) Learning: A Performance Analysis of the Energy Industry Within Distressed Market Conditions**

**Project Description:**  
In this project, we apply LSTM (Long Short-Term Memory networks) and Gradient Boosted Regression (GBR) models to daily historical price data of U.S. energy sector stocks with intraday prices greater than $50.  
Our objectives are to:
- Minimize losses during distressed market periods.
- Assess the performance of deep learning-based asset allocations versus traditional mean-variance allocations under monthly rebalancing.
- Evaluate models using financial performance metrics including Maximum Drawdown, Sortino Ratio, Sharpe Ratio, and Portfolio Turnover.

> **Status:** Currently under development.

---

## 📂 Repository Structure

- `CAPSTONE_NOTEBOOK_1.ipynb` — Initial research, data exploration, and modeling experiments.
- Future folders may include:
  - `data/` — Raw and processed datasets
  - `scripts/` — Python scripts and utilities
  - `models/` — Trained models and evaluation metrics
  - `reports/` — Final analysis and presentation materials
  - `config/` — Configuration files (e.g., paths, hyperparameters)

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn, Plotly
- TensorFlow or PyTorch (TBD)
- Git for version control

---

## 🚀 Getting Started

To set up the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/TechDeo/MScFE-Capstone-Group-9192.git
    cd MScFE-Capstone-Group-9192
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install project dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

---