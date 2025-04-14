# Machine_Learning-Decision_Tree_Detailed_Project
Machine Learning : Decision Tree Classifier Detailed Project for Bank Note Authentication

# 🧾 Bank Note Authentication using Decision Tree Classifier

This project focuses on detecting forged or genuine banknotes using Machine Learning, specifically a Decision Tree Classifier. The model is trained on a dataset consisting of wavelet-transformed features of banknote images.

## 📂 Dataset

The dataset contains 5 columns:

- `variance`
- `skewness`
- `curtosis`
- `entropy`
- `class` (Target: 0 = forged, 1 = genuine)

## 🧠 Objective

To classify whether a banknote is **authentic or forged** based on its physical properties using a supervised learning algorithm.

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked data types, shape, and null values.
- Identified outliers using boxplots and histograms.
- Examined feature distributions and correlation with the target variable.
- Found that:
  - The dataset is clean and balanced.
  - All features are numerical and highly relevant.
  - `variance` and `skewness` show strong correlation with the class label.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib (for EDA & visualizations)
- Scikit-learn (for model training and evaluation)

---

## 🧪 Model Used

- **Decision Tree Classifier** from `sklearn.tree`
- Data split: 80% train, 20% test
- Metrics used:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1-Score)
  - Confusion Matrix

---

## ✅ Model Evaluation

```text
Accuracy Score: 0.985
The classifier performs very well with high precision and recall for both classes.
```

---

## 🚀 How to Run

1. Clone this repo  
   ```bash
   git clone https://github.com/your-username/bank-note-authentication.git
   cd bank-note-authentication
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or Python script.

---

## 💡 Future Improvements

- Visualize the decision tree.
- Try other models like Random Forest or XGBoost.
- Deploy using Flask or Streamlit.
- Containerize the app using Docker.

---

## 🧑‍💻 Author

**Sh shank Verma**  

[LinkedIn](https://www.linkedin.com/in/shshankverma) | [Email](mailto:shshankvermaa@gmail.com)

