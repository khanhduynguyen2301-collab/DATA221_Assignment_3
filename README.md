# DATA 221 Assignment 3 

This repository contains solutions for Assignment #3 of the DATA 221 course. The repo is organized so that **each notebook corresponds to one question** and can be run independently.

---

## File Structure

### Notebooks

- `Question_1.ipynb`  
  Loads `crime.csv`, focuses on `ViolentCrimesPerPop`, computes and prints: **mean, median, std, min, max**, then includes brief comment explanations about skewness and extreme values.

- `Question_2.ipynb`  
  Creates a **histogram** and a **box plot** for `ViolentCrimesPerPop` using matplotlib (with titles + axis labels), then includes **5–7 sentences** of comments interpreting the plots and outliers.

- `Question_3.ipynb`  
  Loads `kidney_disease.csv`, builds `X` (all columns except `classification`) and `y` (`classification`), then performs a **70/30 train-test split** with a fixed `random_state`, with comments explaining why we split.

- `Question_4.ipynb`  
  Trains **KNN (k=5)** on the training set and evaluates on the test set. Prints the **confusion matrix, accuracy, precision, recall, F1**, plus **5–7 sentences** explaining TP/TN/FP/FN and why accuracy alone isn’t enough.

- `Question_5.ipynb`  
  Trains KNN with **k = 1, 3, 5, 7, 9**, stores **test accuracy** for each, prints a small table, identifies the best k, and adds **3–5 sentences** explaining overfitting/underfitting as k changes.

---

## Input Data

- `crime.csv` — used for Q1–Q2  
- `kidney_disease.csv` — used for Q3–Q5 (kidney disease classification)

---

## Notes on Labels

The assignment defines the kidney labels as: **0 = CKD (Positive Class)** and **1 = notckd (Negative Class)**.

---

## Requirements

- Python 3  
- pandas  
- numpy  
- matplotlib  
- scikit-learn (train/test split, KNN, confusion matrix, metrics)
