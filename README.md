# 🏥 Medical Disease Prediction using CNN + BiLSTM + Attention

## 📌 Overview

This project predicts diseases using patient visit history (time-series data).
Instead of treating each visit independently, the model learns patterns across multiple visits to detect disease progression.

---

## 🚀 Key Features

* Time-series modeling of patient visits
* CNN for feature extraction
* BiLSTM for temporal learning
* Attention mechanism for interpretability
* Visualization of important visits

---

## 🧠 Model Architecture

CNN → BiLSTM → Attention → Fully Connected Layer

---

## 📊 Dataset

* Synthetic dataset inspired by MIMIC (ICU dataset)
* Each patient has multiple visits
* 13 medical features
* 3 disease labels:

  * Diabetes
  * Heart Disease
  * Kidney Disease

---

## ⚙️ Workflow

1. Data preprocessing (grouping, sorting)
2. Sequence creation with padding
3. Normalization
4. Model training
5. Evaluation
6. Attention visualization

---

## 📈 Output

* Disease prediction probabilities
* Attention weights showing important visits

---

## 🛠️ Tech Stack

* Python
* PyTorch
* Pandas
* NumPy
* Matplotlib

---

## 📓 Notebook

Run the full implementation here:
medical_time_series_disease_prediction.ipynb

---

## 📄 Documentation

Detailed explanation available in:
codeworkexplanationl.docx

---

## 🎯 Future Improvements

* Use real MIMIC dataset
* Improve model accuracy
* Deploy as web app

---

## 👤 Author

Your Name
