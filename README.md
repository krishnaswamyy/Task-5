# Task 5 – Train-Test Split & Model Evaluation

Objective
The objective of this task is to split the dataset into training and testing sets,
train a machine learning model, and evaluate its performance using standard
evaluation metrics.

---

 Dataset
- **Name:** Heart Disease UCI Dataset
- **Source:** Kaggle
- **Target Variable:** `target`
  - 0 → No heart disease
  - 1 → Presence of heart disease

---

 Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Google Colab

---

 Steps Performed

1. Loaded the dataset into Google Colab
2. Separated features (X) and target variable (y)
3. Split the dataset into training and testing sets
4. Trained a Logistic Regression model
5. Made predictions on the test data
6. Evaluated the model using:
   - Accuracy
   - Precision
   - Recall
   - Confusion Matrix

---

 Evaluation Metrics Explained

- **Accuracy:** Measures overall correctness of the model
- **Precision:** Measures how many predicted positives are actually correct
- **Recall:** Measures how many actual positives were correctly identified
- **Confusion Matrix:** Shows True Positives, True Negatives, False Positives, and False Negatives

---

 Project Files
- `heart.csv` – Dataset file
- `Task-5.ipynb` – Jupyter Notebook with implementation
- `README.md` – Project documentation

---

Conclusion
The model was successfully trained and evaluated using train-test split.
Evaluation metrics provide insights into the model's performance on unseen data.
This task demonstrates the importance of proper data splitting and model evaluation
in machine learning workflows.
