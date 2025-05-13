# Stress-and-Affect-Detection
Stress and Affect Detection

# 🧠 Stress and Affect Detection using Physiological Signals

This project focuses on detecting stress and emotional states using the **WESAD dataset**, a multimodal dataset containing physiological and motion data. By applying **permutation entropy** and **complexity analysis**, we classify affective states like **Baseline**, **Stress**, **Amusement**, and **Meditation** with high accuracy.

## 📊 Objective

To explore time-series physiological data and classify different affective states by computing entropy-complexity features and applying them to various classification techniques.

---

## 🗂 Dataset

- **Source**: [WESAD Dataset](https://archive.ics.uci.edu/ml/datasets/WESAD)
- Contains data from 15 subjects recorded via chest and wrist sensors.
- Modality types: ECG, EMG, EDA, TEMP, RESP, ACC

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical computation
- **Matplotlib & Seaborn** for visualization
- **Scikit-learn** for classification models
- **Permutation entropy** and **complexity measures**

---

## 📌 Key Features

- Extracted **permutation entropy** and **statistical complexity** for 6 physiological modalities.
- Preprocessed data: handled **missing values**, **inconsistencies**, and **outliers**.
- Achieved **98% classification accuracy** using entropy-complexity plots.
- Visualized affective state clusters using 2D scatter plots.

---

## 📈 Results

- Clear separation of emotional states in entropy-complexity space.
- Comparative performance across modalities helped identify the most informative sensors.

---


