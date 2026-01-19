# Parkinson’s Disease Detection (Local ML Project)

This repo is a local, beginner-friendly re-run of the common Kaggle workflow for **Parkinson’s disease detection** using a classic **voice-measurements dataset** (features like jitter/shimmer, etc.) and a binary target column `status`.

You’ll run a Jupyter notebook that:
- loads the dataset from `data/`
- does basic EDA
- trains multiple models (Logistic Regression, SVM, KNN)
- evaluates with accuracy, confusion matrix, and ROC-AUC

---

## Project Structure

parkinsons-ml/
├── data/
│   └── parkinsons.csv     # dataset CSV goes here (name may vary)
├── chanchal24_parkinsons_local_like.ipynb
└── README.md
