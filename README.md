# Ambulance Estimated Time of Arrival (ETA) Prediction

A baseline machine learning project to predict ambulance Estimated Time of Arrival (ETA) using Multiple Linear Regression. Developed as part of a personal portfolio exploring the intersection of Artificial Intelligence and Emergency Medical Services (EMS).

---

## ⚠️ Important Note on Data
**The dataset used in this project is entirely Synthetic.** It was generated programmatically using random distributions to simulate emergency dispatch scenarios (distance, traffic severity, weather). This project serves as a proof-of-concept pipeline and does not utilize real-world EMS data or operational dispatch systems.

---

## 📊 Features
The model relies on three primary features to predict ETA:
1. **Distance:** Travel distance from the base/station to the incident location (km).
2. **Traffic Index:** Traffic congestion level on a scale from 1 (Smooth) to 5 (Heavy).
3. **Weather Condition:** Binary indicator (0 = Clear, 1 = Adverse/Rainy/Snowy).

---

## 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Key Components:**
  * Train/Test Split (80/20)
  * `StandardScaler` for feature scaling
  * Scikit-Learn `Pipeline` to prevent data leakage

---

## 📈 Evaluation Metrics
The model is evaluated on a held-out test set:
* **Root Mean Squared Error (RMSE):** ~2.00 minutes (indicates average prediction error).
* **R-squared ($R^2$):** ~0.95 (proportion of variance explained by the baseline linear features).

---

## 🚀 Future Work & Limitations
Because this is a preliminary baseline model built on synthetic data, several improvements are planned for future iterations:
* **Non-Linear Models:** Testing advanced algorithms like Random Forest or Gradient Boosting to capture complex traffic patterns.
* **Feature Engineering:** Incorporating time-of-day, day-of-week, and specific geographic coordinates.
* **Cross-Validation:** Implementing K-Fold Cross-Validation for more robust performance metrics.
* **Real-World Data:** Transitioning to open-source or institutional emergency response datasets.

---

## 👤 Author
**Mahdi Nasirpour**  
EMS Student | Aspiring Researcher in AI & Healthcare
