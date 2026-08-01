# 🚢 Titanic Data Preprocessing Project

This project is completed as part of **Week 1** of the **Machine Learning & AI Internship** at **Skill Nexis**.

The objective of this project is to clean and preprocess the Titanic dataset before applying Machine Learning algorithms.

---

## 📌 Project Objectives

- Import and explore the dataset
- Handle missing values
- Encode categorical features
- Visualize data
- Save the cleaned dataset

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

Dataset Used:
- Titanic Dataset (Kaggle)

Target:
- Predict passenger survival after preprocessing.

---

## 📋 Tasks Completed

- ✔ Imported the dataset using Pandas
- ✔ Explored the dataset using `info()` and `describe()`
- ✔ Checked missing values
- ✔ Filled missing values
- ✔ Encoded categorical columns (`Sex`, `Embarked`)
- ✔ Visualized Age Distribution
- ✔ Saved the cleaned dataset as a new CSV

---

## 📊 Data Preprocessing Steps

### Missing Values

- Age → Filled using Median
- Embarked → Filled using Mode
- Cabin → Removed (Large number of missing values)

### Encoding

- Sex → Label Encoding
- Embarked → One-Hot Encoding

### Visualization

- Age Distribution Histogram
- Count plots for categorical features

---

## 📁 Project Structure

```
Titanic-Data-Preprocessing/
│
├── dataset/
│   └── train.csv
│
├── notebook/
│   └── Titanic_Preprocessing.ipynb
│
├── output/
│   └── cleaned_titanic.csv
│
├── images/
│   └── age_distribution.png
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/Titanic-Data-Preprocessing.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📈 Sample Output

- Dataset Summary
- Missing Value Analysis
- Encoded Features
- Age Distribution Plot
- Cleaned CSV File

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Data exploration
- Data cleaning
- Missing value handling
- Feature encoding
- Data visualization
- Preparing data for Machine Learning

---

## 👨‍💻 Author

**Ansh Vijay Thakar**

Machine Learning & AI Intern

GitHub: https://github.com/yourusername

---

## 📜 Internship

This project was completed as part of the **Machine Learning & AI Internship** conducted by **Skill Nexis**.

---
