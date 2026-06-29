# CodeAlpha\_CreditScoringModel

## 🚀 Project Title

**Credit Scoring Model using Python and Machine Learning**

---

## 📌 Objective

The objective of this project is to build a **Credit Scoring Classification Model** to predict whether a customer will default on a loan or not, based on their financial history. This is a **binary classification** problem where the target variable is `default` (Yes or No).

---

## 📊 Dataset Information

- **Source:** [Statology GitHub](https://raw.githubusercontent.com/Statology/Python-Guides/main/default.csv)
- **Features:**
  - `student`: Whether the person is a student (Yes/No)
  - `balance`: The balance left on their credit card
  - `income`: Annual income in dollars
  - `default`: Whether they defaulted on their payment (target)

Dataset is preprocessed using Label Encoding for categorical variables.

---

## ⚙️ Tools & Libraries Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🧪 ML Workflow

1. **Data Collection:** Loaded the dataset from a public URL.
2. **Preprocessing:** Encoded categorical variables (`student`, `default`)
3. **Train-Test Split:** 80/20 split for training and evaluation
4. **Model Training:** Random Forest Classifier
5. **Model Evaluation:**
   - Confusion Matrix
   - Classification Report
   - ROC AUC Score
   - Feature Importance Plot

---

## 📈 Model Performance

- **Accuracy:** 96%
- **Precision for class 0:** 0.97
- **Recall for class 1:** 0.29
- **ROC AUC Score:** 0.86

While the model performs well overall, the **recall for class 1 (defaults)** is low, which means it struggles to catch actual defaulters. Future improvements could include class balancing or different algorithms.

---

## 📷 Screenshots

All plots and results are available in the `screenshots/` folder:

- `confusion_matrix.png`
- `roc_curve.png`
- `feature_importance.png`

---

## 📁 File Structure

```
├── credit_model.ipynb           # Main code notebook
├── data_info.txt                # Dataset URL and description
├── README.md                    # Project description
├── screenshots/                 # Output visualizations
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
```

---

## 🏁 Conclusion

This project demonstrates how Machine Learning models can be used to evaluate creditworthiness. The Random Forest classifier was effective in predicting defaults with high accuracy, but additional steps like balancing or hyperparameter tuning could improve the recall for minority classes.

---

## 🙌 Acknowledgements

Thanks to **CodeAlpha** for this internship opportunity and the hands-on project experience.

---

## 🔗 Author

- **Name:** Manikanta Pallepati  
- **GitHub:** [pallepa](https://github.com/Manikanta545)


---

> *This project is part of the CodeAlpha Machine Learning Internship.*

