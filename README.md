# Kaggle – TPU Getting Started

![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue?logo=kaggle)  
**Image classification project using TPUs** – Kaggle "TPU Getting Started" competition.  
This repository contains the complete pipeline: data preprocessing, model training, evaluation, and submission.

----

## Competition Overview
The ["TPU Getting Started"](https://www.kaggle.com/competitions/tpu-getting-started) competition is designed to help participants learn how to train deep learning models using **Tensor Processing Units (TPUs)** for image classification.

The dataset contains labeled images of **flowers** (daisy, dandelion, rose, sunflower, tulip) to be classified into the correct category.

---

## Project Goals
- Train a deep learning model (CNN) for flower image classification
- Leverage **TPU acceleration** for faster training
- Build a **reproducible pipeline** from data download to final submission
- Optimize performance using data augmentation and hyperparameter tuning

---

## Repository Structure
```
kaggle-tpu-getting-started/
│
├── notebooks/ # Jupyter Notebooks
│ ├── EDA.ipynb # Exploratory Data Analysis
│ ├── training.ipynb # Model training
│ └── inference.ipynb # Final predictions & submission
│
├── src/ # Reusable Python code
│ ├── data_loader.py # Dataset download & preprocessing
│ ├── model.py # Model architecture definition
│ └── utils.py # Helper functions
│
├── data/ # Local datasets (not tracked by Git)
│ └── README.md # Instructions to download the data
│
├── outputs/ # Results & submission files
│
├── requirements.txt # Python dependencies
├── README.md # Project description
└── .gitignore # Ignored files & folders
```
