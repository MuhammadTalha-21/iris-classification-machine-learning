# 🌸 Iris Flower Classification using Machine Learning

A complete Machine Learning project that classifies Iris flower species using multiple classification algorithms. This project demonstrates the full ML workflow, including data preprocessing, visualization, model training, evaluation, hyperparameter tuning, model comparison, model persistence, and real-time prediction.

---

## 📌 Project Overview

The goal of this project is to accurately classify Iris flowers into one of three species:

* **Setosa**
* **Versicolor**
* **Virginica**

The project begins with a K-Nearest Neighbors (KNN) model and is further enhanced with model optimization, cross-validation, and comparison against other popular machine learning algorithms.

---

# 🚀 Features

* 📊 Iris Dataset Analysis
* 🧹 Data Preprocessing
* 📈 Exploratory Data Analysis (EDA)
* 🌸 Pair Plot Visualization
* 🔍 Missing Value Detection
* ⚖️ Feature Scaling using StandardScaler
* 🤖 K-Nearest Neighbors (KNN) Classification
* 📉 Confusion Matrix
* 📋 Classification Report
* ✅ Accuracy Evaluation
* 🔄 K-Fold Cross Validation
* ⚙️ Hyperparameter Tuning using GridSearchCV
* 📊 Model Comparison

  * KNN
  * Logistic Regression
  * Support Vector Machine (SVM)
  * Decision Tree
* 💾 Save & Load Trained Model using Joblib
* 🌼 Real-Time Iris Species Prediction Function

---

# 🛠 Technologies Used

* Python 3
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn


---

# 📂 Project Structure

```
Iris-Classification/
│
├── p2_iris_classification_knn_model.py
├── README.md
```

---

# 📊 Machine Learning Workflow

1. Import Libraries
2. Load Iris Dataset
3. Data Exploration
4. Data Visualization
5. Data Preprocessing
6. Feature Scaling
7. Train-Test Split
8. KNN Model Training
9. Model Evaluation
10. Confusion Matrix
11. Classification Report
12. Cross Validation
13. Hyperparameter Tuning
14. Model Comparison
15. Save Trained Model
16. Prediction Interface

---

# 🤖 Models Used

| Model                  | Purpose                      |
| ---------------------- | ---------------------------- |
| K-Nearest Neighbors    | Baseline Classification      |
| Logistic Regression    | Performance Comparison       |
| Support Vector Machine | High Accuracy Classification |
| Decision Tree          | Comparative Analysis         |

---

# 📈 Evaluation Metrics

The project evaluates model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation Score
* Mean Accuracy
* Standard Deviation

---

# 💾 Model Persistence

The trained KNN model is saved using **Joblib**, allowing it to be reused without retraining.

```python
joblib.dump(model, "knn_iris_model.joblib")
```

Later it can be loaded with:

```python
model = joblib.load("knn_iris_model.joblib")
```

---

# 🌼 Example Prediction

```python
predict_iris_species(
    sepal_length=5.1,
    sepal_width=3.5,
    petal_length=1.4,
    petal_width=0.2
)
```

Output:

```
Setosa
```

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/iris-flower-classification.git
```

Move into the project directory:

```bash
cd iris-flower-classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python p2_iris_classification_knn_model.py
```

---

# 📚 Libraries Required

```text
scikit-learn
numpy
pandas
matplotlib
seaborn
joblib
```

---

# 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

* Data Preprocessing
* Feature Engineering
* Classification Algorithms
* Model Evaluation
* Hyperparameter Optimization
* Cross Validation
* Data Visualization
* Machine Learning Pipeline
* Model Deployment Preparation

---

# 🔮 Future Improvements

* Streamlit Web App
* Flask API
* Real-time User Interface
* Model Deployment
* Docker Support
* Cloud Deployment
* Interactive Dashboard

---

# 👨‍💻 Author

**Muhammad Talha**

Artificial Intelligence Intern

Python | Machine Learning | Data Science

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support is greatly appreciated!
