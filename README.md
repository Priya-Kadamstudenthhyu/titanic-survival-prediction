# 🚢 Titanic Survival Prediction

## 🎯 Objective
Build a machine learning model to predict whether a passenger survived the Titanic disaster using structured data.

---

## 📦 Dataset Features
- `Pclass`: Passenger class
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Ticket fare
- `Embarked`: Port of embarkation
- `Survived`: Target variable (0 = No, 1 = Yes)

---

## 🧼 Data Preprocessing
- Dropped unused columns: `PassengerId`, `Name`, `Ticket`, `Cabin`
- Handled missing values in `Age` and `Embarked`
- Encoded categorical features: `Sex`, `Embarked`
- Normalized numerical features: `Age`, `Fare`

---

## 🧠 Model Used
**RandomForestClassifier**  
- Train/Test Split: 80/20  
- Tuned for high accuracy  
- Evaluated using Accuracy, Precision, Recall, F1-score

---

## 📊 Performance

| Metric     | Score |
|------------|-------|
| Accuracy   | 1.00  |
| Precision  | 1.00  |
| Recall     | 1.00  |
| F1 Score   | 1.00  |

---

## ▶️ How to Run
1. Open the notebook `titanic_model.ipynb` in Google Colab.
2. Run each cell sequentially.
3. Ensure `tested.csv` is available in the same directory or upload it in Colab.

---

## ✅ Conclusion
The model achieves **perfect classification** on the test data. Further improvement could involve cross-validation and trying different models for robustness.

---

## 📌 Author
[Priya Kadam](https://github.com/Priya-Kadamstudenthhyu)
