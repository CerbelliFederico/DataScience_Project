# Age Prediction from Audio

This project focuses on predicting the **age of a speaker** from audio data using machine learning. It includes:

- **Data preprocessing** and feature cleaning  
- **Additional audio feature extraction** (MFCCs, Chroma)  
- **Regression modeling** with K-Nearest Neighbors (KNN), Random Forest (RF), and Support Vector Regression (SVR)  

---
## Folder Structure

DataScience_Project/
├── datasets/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks with the workflow
└── report.pdf # Full project report with detailed explanations

---
## How to Use

1. Open the notebooks in order, starting with `1_feature_extraction_preprocessing.ipynb`.  
2. Ensure the `datasets/` folder is present.  
3. Install required Python package

---
## Datasets

- **Raw datasets:** `development.csv` and `evaluation.csv`  
- **Processed datasets:** `train_filtered.csv`, `evaluation_filtered.csv`, `predictions.csv`  

> The raw datasets are included for completeness. Notebooks 2, 3, and 4 use the processed datasets for modeling.  
> For space reasons, the audio files are **not included** in this repository.

---
## Notes

The notebooks are cleaned and annotated for clarity.
File paths assume the folder structure shown above.
Audio features include MFCCs, Chroma, pitch, energy, jitter, shimmer, and other extracted metrics.

---
## Report
For a detailed explanation of the dataset, preprocessing steps, feature extraction, and model evaluation, see report.pdf included in this repository
