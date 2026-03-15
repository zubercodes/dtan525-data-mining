# DTAN-525: Data Mining Concepts
### Indiana Wesleyan University — Mohammad Zuber Vohra

---

## Course Overview

This repository contains all Python data mining practice notebooks, HTML exports, and written assignments for **DTAN-525: Data Mining Concepts** at Indiana Wesleyan University. The course covers classification, transformers, data preprocessing, and predictive modeling using Python and scikit-learn, based on the textbook *Learning Data Mining with Python* (Harrington, 2012).

---

## Repository Structure

```
dtan525-data-mining/
│
├── notebooks/                  # Jupyter Notebook source files (.ipynb)
│   ├── WS2_Chapter2_Classification.ipynb
│   └── WS2_Chapter5_Transformers.ipynb
│
├── html_exports/               # Exported HTML files for submission
│   ├── DTAN525_WS2_Python_practice_Chapter2_MohammadZuberVohra.html
│   └── DTAN525_WS2_Python_practice_Chapter5_MohammadZuberVohra.html
│
├── assignments/                # Written Q&A and reflection documents
│   └── DTAN525_WS2_QandA_MohammadZuberVohra_v2.docx
│
├── data/                       # Local datasets (gitignored if large)
│   └── .gitkeep
│
├── utils/                      # Shared helper functions
│   └── helpers.py
│
├── requirements.txt            # Python dependencies
├── .gitignore
└── README.md
```

---

## Workshops

### Workshop 2 — Classification & Transformers

| File | Description |
|------|-------------|
| `notebooks/WS2_Chapter2_Classification.ipynb` | OneR, Naive Bayes, Decision Tree on Iris & 20 Newsgroups |
| `notebooks/WS2_Chapter5_Transformers.ipynb` | StandardScaler, MinMaxScaler, OneHotEncoder, PCA, Pipeline, ColumnTransformer |
| `html_exports/..._Chapter2_...html` | Executed HTML export of Chapter 2 notebook |
| `html_exports/..._Chapter5_...html` | Executed HTML export of Chapter 5 notebook |
| `assignments/..._QandA_...docx` | Written Q&A assignment (APA 7 format) |

---

## Topics Covered

### Chapter 2 — Classification
- **OneR Classifier** — single-rule baseline classifier
- **Gaussian Naive Bayes** — numeric classification on Iris dataset
- **Multinomial Naive Bayes** — text classification on 20 Newsgroups
- **Decision Tree** — rule-based classification with feature importance
- **TF-IDF Vectorization** — text feature extraction
- **Cross-validation** — model evaluation with 5-fold CV
- **Confusion Matrix & Classification Report** — performance metrics

### Chapter 5 — Transformers & Data Preprocessing
- **StandardScaler** — zero mean, unit variance normalization
- **MinMaxScaler** — scaling to [0, 1] range
- **Binarizer** — threshold-based binary transformation
- **LabelEncoder** — categorical target encoding
- **OneHotEncoder** — categorical feature encoding
- **SimpleImputer** — missing value handling
- **PolynomialFeatures** — feature engineering
- **PCA** — dimensionality reduction
- **Pipeline** — chaining transformers + classifiers
- **ColumnTransformer** — mixed-type data preprocessing

---

## Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/mohammadzubervohra/dtan525-data-mining.git
cd dtan525-data-mining
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## Key Results

| Classifier | Dataset | Test Accuracy |
|---|---|---|
| OneR | Iris | 73.33% |
| Gaussian Naive Bayes | Iris | 96.67% |
| Decision Tree (depth=3) | Iris | 100.00% |
| Multinomial Naive Bayes | 20 Newsgroups | 89.12% |
| Pipeline: StandardScaler + LR | Iris | 100.00% |
| Pipeline: StandardScaler + PCA + DT | Iris | 93.33% |

---

## References

- Harrington, P. (2012). *Machine Learning in Action*. Manning Publications.
- Pedregosa, F., et al. (2011). Scikit-learn: Machine learning in Python. *Journal of Machine Learning Research, 12*, 2825–2830. https://jmlr.org/papers/v12/pedregosa11a.html
- Han, J., Kamber, M., & Pei, J. (2012). *Data Mining: Concepts and Techniques*. Morgan Kaufmann.
- Scikit-learn developers. (2024). *Preprocessing and Transformations*. https://scikit-learn.org/stable/modules/preprocessing.html
- Scikit-learn developers. (2024). *Dataset Transformations*. https://scikit-learn.org/stable/data_transforms.html

---

## Author

**Mohammad Zuber Vohra**
M.S. Management, Data Analytics Specialization — Indiana Wesleyan University (May 2026)
📧 mo.zubervohra24@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/mohammad-zuber-vohra-55b827156/)
