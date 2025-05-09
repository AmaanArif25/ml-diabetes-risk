# 📊 How to Use: Diabetes Risk Prediction Model

Follow these simple steps to use the diabetes prediction model:

---

## 🔧 Prerequisites

Make sure you have the following installed:
- Python 3.x
- pandas
- scikit-learn
- joblib

---

## 🚀 Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AmaanArif25/diabetes-risk-prediction.git
   
2. Load the model in your Python script or notebook:
   ```bash
   import joblib
   model = joblib.load('modelForPrediction.pkl')

3. Prepare your input data:
   ```bash
   sample_input = [[5, 166, 72, 19, 175, 25.8, 0.587, 51]]  # Example features

4. Predict diabetes risk:
   ```bash
   prediction = model.predict(sample_input)
   print("Prediction:", "Diabetic" if prediction[0] == 1 else "Not Diabetic")

---

## 🧠 Note
This model is trained for educational purposes and may not reflect clinical-grade accuracy. Use responsibly.

---

Made with ❤️ by **Amaan Arif**
