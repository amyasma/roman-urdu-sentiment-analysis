# Roman Urdu Sentiment Classification – Modeling Experiment

## Overview

This project focuses on sentiment classification for Roman Urdu text using a publicly available dataset. The notebook implements a complete machine learning pipeline using Python and scikit-learn, aimed at evaluating how well traditional NLP techniques perform on Roman Urdu.

The analysis includes the following key components:
- TF-IDF vectorization to convert textual data into numerical features.
- Label encoding for sentiment classes.
- Training and evaluation of a baseline classifier using Logistic Regression.
- Model performance assessment using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

Roman Urdu presents unique linguistic challenges due to its informal structure, inconsistent spelling, and colloquial usage. This project explores those complexities and provides a foundational modeling approach that can be extended to more advanced methods or multilingual NLP research.

## Dataset

The dataset used in this project is sourced from Hugging Face:

**[romanurdu-sentiment-dataset](https://huggingface.co/datasets/HowMannyMore/romanurdu-sentiment-dataset)**  
It includes Roman Urdu text samples labeled with sentiment categories, suitable for classification tasks in natural language processing.

## Requirements

To run the Project.ipynb notebook, ensure the following are installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

You can install the necessary packages using:

```bash
pip install -r requirements.txt
