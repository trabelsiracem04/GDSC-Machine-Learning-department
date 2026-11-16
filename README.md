# Machine Learning Department Sessions — GDSC ENET'Com

A curated repository of training materials, slide decks, interactive Jupyter notebooks, datasets, and cheat sheets developed by the Machine Learning Department at **Google Developer Student Clubs (GDSC) ENET'Com**, Sfax, Tunisia.

---

## Repository Structure

```text
GDSC-ML-departement/
├── code/               # Practice templates and complete reference notebooks (.ipynb)
├── datasets/           # Tabular workshop datasets (CSV)
├── Presentations/      # Technical workshop slide decks (PDF)
└── resume/             # High-yield cheat sheets, summaries, and infographics
```

---

## Workshop Roadmap & Sessions

| Session / Module | Focus & Core Topics | Slides | Hands-on Code | Reference / Cheat Sheets |
| :--- | :--- | :--- | :--- | :--- |
| **Session 1** | **Introduction to Artificial Intelligence**<br>• History of AI: Turing test (1950) to Generative AI<br>• Taxonomy: AI vs. Machine Learning vs. Deep Learning<br>• Classical programming vs. ML paradigms<br>• Learning types: Supervised, Unsupervised, RL | [Slides](Presentations/Ai_Introduction%20.pdf) | — | — |
| **Session 2** | **Linear Regression from Scratch**<br>• Hypothesis function: $y' = w_1x_1 + b$<br>• Loss functions: $L_1, L_2$, MAE, MSE, RMSE<br>• Optimization: Gradient Descent & learning rate tuning | [Slides](Presentations/Linear_Regression.pdf) | — | [Formulas & Concepts PNG](resume/linear_regression_cheat_sheet.png) |
| **Session 3** | **Logistic Regression & Classification**<br>• Sigmoid activation, log odds & decision boundaries<br>• Maximum Likelihood Estimation (MLE) & Log Loss<br>• Regularization ($L_1/L_2$), ROC-AUC, Precision/Recall | [Slides](Presentations/Logistic%20Regression%20.pdf) | [Breast Cancer Diagnostic](code/Logistic_Regression_Breast_Cancer%20.ipynb)<br>[Bank Marketing Lab](code/bank_marketing.ipynb) | [Pandas Operations PNG](resume/pandas_cheat_sheet.png) |
| **Bootcamp** | **End-to-End Data Science Workflow**<br>• Mathematical problem framing & the 6-step ML cycle<br>• Exploratory Data Analysis (EDA) & missing value handling<br>• Outlier detection (IQR, Z-score) & feature visualization | [Slides](Presentations/Bootcamp_Data_Science.pdf) | [Starter Lab](code/Bootcamp_telco_churn.ipynb)<br>[Completed Solution](code/Bootcamp_telco_churn_completed.ipynb) | [Pandas & EDA PDF](resume/Data_Science_sheet_cheat.pdf)<br>[Telco ML Workflow PDF](resume/Data_science_telco_sheet_cheat.pdf) |

---

## Datasets

| Dataset | Source / Location | Dimensions | Task Type | Description |
| :--- | :--- | :--- | :--- | :--- |
| **Telco Customer Churn** | [`datasets/telco.csv`](datasets/telco.csv) | 7,043 × 21 | Binary Classification | Predict customer subscription churn based on service usage and demographics. |
| **Breast Cancer Wisconsin** | `sklearn.datasets.load_breast_cancer` | 569 × 30 | Binary Classification | Diagnostic classification of cell nucleus characteristics (Malignant vs. Benign). |
| **Bank Marketing** | UCI ML Repository (`ucimlrepo` ID: 222) | 45,211 × 16 | Binary Classification | Predict term deposit subscriptions from direct telemarketing campaigns. |

---

## Quick Start & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/trabelsiracem04/GDSC-Machine-Learning-department.git
cd GDSC-Machine-Learning-department
```

### 2. Configure Environment & Dependencies

```bash
# Create and activate virtual environment
python -m venv venv

# Windows (PowerShell):
.\venv\Scripts\Activate.ps1

# Linux / macOS:
source venv/bin/activate

# Install required dependencies
pip install numpy pandas matplotlib seaborn scikit-learn scipy ucimlrepo jupyterlab
```

### 3. Launch Notebooks
```bash
jupyter lab
```
Navigate to [`code/`](code/) to start with the interactive exercises.

---

## Attribution & Chapter Info

* **Department Leads:** Racem Trabelsi & Sayma Chorfene — Machine Learning Department Leads
* **Organization:** [GDSC ENET'Com](https://www.gdsc-enetcom.tech/), École Nationale d'Électronique et des Télécommunications de Sfax, Tunisia
