# 🚬 Smoking Status Prediction - Data Visualization

This repository contains an exploratory data analysis and visualization of smoking habits based on age using the **"smoker-status-prediction"** dataset curated from **Kaggle**.

---

## 📂 Dataset

- **Source**: [Kaggle - Smoker Status Prediction](https://www.kaggle.com/)
- **File used**: `train_dataset.csv`
- **Features Analyzed**:
  - `age`: Age of individuals
  - `smoking`: Smoking status (0 = Non-smoker, 1 = Smoker)

---

## 📊 Objective

To **visualize and analyze the distribution** of smokers and non-smokers by age groups, and **identify smoking trends** across different ages.

---

## 🧪 Analysis Summary

- A categorical bar plot shows:
  - 🟢 ~60%-65% of the population are **non-smokers**
  - 🔴 ~30%-35% of the population are **smokers**

- Age-wise analysis reveals:
  - 🔺 Around **55% of individuals aged 35** are smokers
  - 🔺 The **age group of 20 years** also has ~50% smokers
  - 🔻 After age 40, the percentage of smokers **steeply declines**

---

## 📌 Conclusion

The data shows that smoking is **most prevalent among individuals aged 20–35**. After 40, smoking habits decrease drastically.  
This may indicate:
- Increased awareness of health issues  
- Lifestyle changes with age  
- Possible drop in numbers due to smoking-related illnesses

---

## 🧰 Tools Used

- Python 🐍
- Pandas 📊
- Seaborn 🎨
- Matplotlib 📈

---

## 📸 Visualizations

1. **Smoker vs Non-Smoker Bar Plot**
2. **Age-wise Smoking Distribution Bar Plot**

---

## ▶️ Getting Started

```python
# Clone the repo or upload notebook to Kaggle/Colab
import pandas as pd
df = pd.read_csv("train_dataset.csv")
