# Intelligent Text Sentiment Analysis and Emotion Classification

Artificial Intelligence Lab project — Second Semester 2025–2026, Faculty of Computing and Information Technology, Information and Computer Science Department, Al-Aqsa University.

## Overview

An NLP pipeline that classifies short text sentences into emotion categories (e.g. joy, sadness, anger, fear, love, surprise), trained on the **Emotions Dataset for NLP** (Kaggle).

**Achieved accuracy: 90.35%**

## Pipeline

1. **Environment setup** — pandas, matplotlib, seaborn, NLTK, scikit-learn.
2. **Data loading** — combines the train/validation/test emotion dataset splits.
3. **Exploratory Data Analysis** — class distribution and dataset structure inspection.
4. **Preprocessing & cleaning** — lowercasing, punctuation/number removal, stopword filtering.
5. **Feature extraction** — TF-IDF vectorization.
6. **Model training & evaluation** — Linear Support Vector Classifier (`LinearSVC`).
7. **Real-world prediction test** — a helper function to classify new, custom sentences.
8. **Interactive web interface** — a bilingual Gradio app for live demo/testing.

## Repository Contents

```
.
└── project.ipynb   # Full Jupyter notebook: EDA, preprocessing, training, evaluation, Gradio demo
```

## How to Run

1. Install the dependencies:
   ```bash
   pip install pandas matplotlib seaborn nltk scikit-learn gradio
   ```
2. Download the **Emotions Dataset for NLP** from Kaggle: https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp
3. Open `project.ipynb` in Jupyter Notebook / JupyterLab and run the cells in order.
