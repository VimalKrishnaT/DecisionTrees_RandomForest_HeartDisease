# Task 5 - Decision Trees & Random Forests (Heart Disease Dataset)

## 📌 Overview
This project is part of my AI & ML internship.  
It focuses on building and evaluating **Decision Tree** and **Random Forest** models using the **Heart Disease dataset**.  
The main goals are to:
1. Train and visualize a Decision Tree.
2. Analyze overfitting and control tree depth.
3. Train a Random Forest and compare accuracy.
4. Interpret feature importances.
5. Evaluate models using cross-validation.

---

## 📂 Dataset
- **Name:** Heart Disease Dataset (`heart.csv`)
- **Target column:** `target` (1 → Disease present, 0 → No disease)
- **Source:** UCI Machine Learning Repository or Kaggle

---
## 📂 Files in Repository

- DecisionTrees_RandomForests.ipynb → Jupyter notebook with code, outputs & plots.

- heart.csv → Dataset file.

- best_decision_tree.pkl → Saved tuned Decision Tree model.

- random_forest.pkl → Saved Random Forest model.

README.md → This file.
---

## ⚙️ Steps Followed
1. **Train a Decision Tree Classifier** and visualize the tree.
2. **Analyze overfitting** using train vs CV accuracy plot and control tree depth.
3. **Train a Random Forest** and compare with the Decision Tree.
4. **Interpret feature importances** from the Random Forest.
5. **Evaluate** both models using cross-validation.

---

## 🛠️ Technologies Used
- Python 3
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

## 📊 Results Summary
| Model           | Test Accuracy| CV Mean Accuracy |
|-----------------|--------------|------------------|
| Decision Tree   | 87.31%       | 98.44%           |
| Random Forest   | 100%         | 99.70%           |

> Replace XX with your actual results after running the code.

---

## 📷 Visuals
- Decision Tree visualization (first 3 levels)
- Train vs CV accuracy plot (overfitting analysis)
- Feature importance bar chart

---
