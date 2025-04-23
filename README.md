# 🎓 Student Performance Prediction Using Machine Learning

This project aims to predict student performance levels (High, Medium, Low) using various machine learning models. The goal is to assist educational institutions in identifying students who may need academic support or recognition based on their predicted performance.

---

## 📌 Project Objective

To build and evaluate multiple machine learning classifiers to categorize students into three performance levels based on input features such as test scores, attendance, and assignment records.

---

## 🧠 Algorithms Used

The following machine learning models were implemented and compared:

1. **Decision Tree Classifier**
2. **Random Forest Classifier**
3. **Linear Model - Perceptron**
4. **Linear Model - Logistic Regression**
5. **Multi-Layer Perceptron (MLP Classifier / Neural Network)**

---

## 📂 Dataset

- The dataset contains features related to student behavior and academics.
- Target variable: `Performance Category`
  - 0 = High Performer
  - 1 = Medium Performer
  - 2 = Low Performer

---

## ⚙️ Model Evaluation Metrics

Each model was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

---

## 📊 Results Summary

| Model                       | Accuracy | Best Precision | Weakest Recall |
|----------------------------|----------|----------------|----------------|
| Decision Tree              | 67.8%    | Class 1 (0.89) | Class 2 (0.59) |
| Random Forest              | 70.6%    | Class 1 (0.93) | Class 2 (0.62) |
| Linear Perceptron          | 39.2%    | Class 1 (1.00) | Class 2 (0.00) |
| Logistic Regression        | 76.2%    | Class 1 (0.93) | Class 2 (0.62) |
| MLP Classifier (NeuralNet) | 74.1%    | Class 1 (0.92) | Class 2 (0.62) |

> 🔎 Logistic Regression and MLP Classifier showed the best overall performance.

---

## 📈 Key Insights

- **Class 1 (Medium performers)** is the easiest to classify with high precision and recall.
- **Class 2 (Low performers)** is the most difficult to classify accurately.
- **Logistic Regression and MLP** provide the best balance between precision and recall across all classes.

---

## 🛠️ Tools and Technologies

- Python
- Pandas, NumPy
- Scikit-learn (sklearn)
- Jupyter Notebook / VS Code

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-prediction.git
   cd student-performance-prediction
