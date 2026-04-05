# Colon Cancer Tissue Analysis

This project compares a **CNN trained from scratch** with a **transfer learning model (MobileNetV2)** for multiclass colorectal histology tissue classification.

## Project Objective

The goal of this project is to classify colorectal histology image patches into 8 tissue classes and evaluate whether transfer learning improves performance and generalization compared to a baseline CNN.

## Dataset

This project uses the **Colorectal Histology MNIST / Kather Histology Dataset** from Kaggle.

### Classes
- 01_TUMOR
- 02_STROMA
- 03_COMPLEX
- 04_LYMPHO
- 05_DEBRIS
- 06_MUCOSA
- 07_ADIPOSE
- 08_EMPTY

### Dataset Notes
- 5000 image patches
- Image size: 150 × 150
- Balanced dataset with approximately 625 samples per class
- Original `.tif` images were converted to `.png` for TensorFlow compatibility

## Project Structure

```text
COLON-CANCER-TISSUE-ANALYSIS/
├── data/
├── models/
├── notebooks/
│   └── colon_cnn_projects.ipynb
├── results/
│   ├── metrics/
│   └── plots/
├── src/
└── LICENSE