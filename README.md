# 🧠 Thyroid Cancer Detection with Machine Learning & Explainable AI

This project presents a hybrid machine learning and deep learning framework for classifying thyroid nodules (benign vs malignant) using TI-RADS ultrasound data and image features, with integrated explainability for medical decision-making.

---

## 🚀 Project Highlights

- ✅ Binary classification based on TI-RADS score
- ⚙️ Traditional ML (XGBoost, Random Forest) + Deep Learning (CNN via PyTorch)
- ⚖️ Balanced class distribution using SMOTE
- 📈 SHAP & Grad-CAM for model interpretability
- 🧪 Visual performance reports (ROC, confusion matrix)

---

## 🗂️ Folder Structure

- `data/`: Ultrasound image data and feature spreadsheets
- `models/`: Trained models in `.pkl` and `.pth` formats
- `results/`: Confusion matrix, ROC curves, SHAP heatmaps
- `src/`: Core scripts for preprocessing, training, and testing
- `notebooks/`: Jupyter analysis notebooks
- `requirements.txt`: List of dependencies

---

## 📊 Features Used

- **TI-RADS score**
- **Nodule composition**
- **Calcification presence**
- **Centroid, area, perimeter (spatial features)**


