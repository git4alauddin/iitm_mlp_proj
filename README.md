# 🧠 Bank Marketing Prediction

> A compact, end-to-end ML project to predict if a client subscribes to a term deposit.  
> Focused on clean preprocessing, model comparison, and evaluation.

---

## 📂 Dataset

| File | Description |
|------|--------------|
| `bank_train.csv` | Training data (~39K rows, 17 features) |
| `bank_test.csv`  | Test data |

**Target:** `target` → `yes / no`

---

## ⚙️ Workflow

1. **Data Cleaning & Imputation**
2. **Feature Engineering** → `days_since_contact`, `balance_category`, `financial_risk`
3. **Encoding + Scaling** → `OrdinalEncoder`, `OneHotEncoder`, `StandardScaler`
4. **Model Training** → `Logistic Regression`, `Random Forest`, `XGBoost`
5. **Evaluation** → F1 · Accuracy · ROC-AUC · Precision–Recall

---

## 📊 Results

| Model | F1 | Accuracy | AUC |
|:--|:--:|:--:|:--:|
| Logistic Regression | 0.71 | 0.81 | 0.80 |
| Random Forest | 0.77 | 0.85 | 0.91 |
| **XGBoost** | **0.77** | **0.86** | **0.91** |

**Top drivers:** longer call duration ↑ · higher balance ↑ → higher subscription chance

---

## 🧰 Tech Stack

`Python` · `Pandas` · `Scikit-learn` · `XGBoost` · `Matplotlib`

---

## 🎯 Outcome

✅ Built a reproducible ML pipeline  
✅ Compared linear vs ensemble models  
✅ Visualized metrics (ROC · PR · Confusion Matrix)

---

*A simple, clear project — perfect for mastering ML fundamentals.*
