# Personal Loan Prediction using Artificial Neural Networks (ANN)

This project demonstrates the use of an Artificial Neural Network (ANN) to predict whether a customer will accept a personal loan offer. The model is trained on demographic and financial data from a bank marketing dataset.

---

## 📊 Objective

To develop a deep learning classification model that predicts personal loan acceptance, supporting better customer targeting for financial institutions.

---

## 📁 Dataset

- **Source:** Bank marketing dataset
- **Rows:** ~5,000 customers
- **Features:** Age, Income, Education, Mortgage, Credit Card usage, etc.
- **Target:** `Personal Loan` (0 = No, 1 = Yes)

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- TensorFlow / Keras
- scikit-learn (train_test_split, accuracy_score, classification_report)

---

## 🧪 Workflow

1. Load and inspect the dataset
2. Clean missing values and encode categorical variables
3. Scale features and split into train/test sets
4. Build and train an ANN using Keras
5. Evaluate model using accuracy and F1 score

---

## 🧠 Model Results

| Metric         | Value |
|----------------|--------|
| Accuracy       | 91%   |
| F1 Score       | 0.90  |

---

## ✅ Conclusion

- The ANN model achieved high classification performance on the test set.
- Most influential features included **Income**, **Education**, and **Mortgage**.
- This model can help financial institutions automate loan targeting and improve campaign success rates through data-driven decisions.

---

## 📎 Author

**Jaymin Patel**  
[GitHub Portfolio](https://jayminmech7.github.io)
