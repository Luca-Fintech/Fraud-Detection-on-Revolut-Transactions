# Fraud Detection on Revolut Transactions

End-to-end fraud detection project on 1M+ Revolut transactions.  
Includes advanced feature engineering, imbalanced learning (SMOTE, boosting, stacking), robust benchmarking, and clear visualizations. Code is fully reproducible, modular, and ready for industrial adaptation.

---

## 🚀 Project Highlights

- **Real-world banking dataset** (1M+ transactions)
- **Complete ML pipeline:** data cleaning, feature engineering, model training & evaluation
- **Imbalanced data handling:** SMOTE, BorderlineSMOTE, BalancedRandomForest
- **Modeling:** Logistic Regression, Random Forest, XGBoost, LightGBM, Stacking, etc.
- **Robust metric analysis:** ROC-AUC, PR-AUC, F1-Score, recall/precision tuning
- **Clear visualizations** (Plotly, seaborn, matplotlib)
- **Ready for production:** modular code, versioned, can be extended to APIs/Streamlit

---

## 📦 Dataset

The raw data files are **NOT included** in this repository (file size limits).  
You need to download them from Kaggle and place them in the `/data` folder:

- [transactions.csv](https://www.kaggle.com/datasets/andrejzuba/revolutassignment/data?select=transactions.csv)
- [users.csv](https://www.kaggle.com/datasets/andrejzuba/revolutassignment/data?select=users.csv)
- [fraudsters.csv](https://www.kaggle.com/datasets/andrejzuba/revolutassignment/data?select=fraudsters.csv)

Directory structure after download:

Fraud-Detection-on-Revolut-Transactions/
│
├── data/
│ ├── transactions.csv
│ ├── users.csv
│ └── fraudsters.csv
│
├── project.ipynb
├── pyproject.toml
└── README.md


---

## 🛠️ Environment & Dependencies (Poetry)

This project uses [Poetry](https://python-poetry.org/) for dependency management and reproducible environments.

### 1. **Install Poetry** (if not already installed)
```bash 
pip install poetry

2. Install the project dependencies
poetry install

3. Activate the poetry environment
poetry shell

📒 Run the Notebook
After activating your environment with Poetry and downloading the datasets,
open and run project.ipynb with Jupyter (or VSCode, Colab, etc.):

jupyter notebook
or
jupyter lab

📝 Notebooks
project.ipynb — full code, explanations, and results.

📣 Notes

Data files are not provided in this repo.

Download from Kaggle, place in /data/, and you're ready to run.

All results are reproducible with the provided code and environment.

