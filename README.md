# 🌸 Iris Flower Classification

A machine learning project that classifies iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — using their sepal and petal dimensions. This project demonstrates a complete ML pipeline from data exploration to model evaluation, making it an excellent introduction to supervised learning.

---

## 📊 Dataset

- **Source:** [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) (Fisher’s Iris dataset, 1936)  
- **Samples:** 150  
- **Features (in cm):**  
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  
- **Classes (target):**  
  - Iris Setosa  
  - Iris Versicolor  
  - Iris Virginica  

The dataset is balanced, with 50 samples per class.

---

## 🔑 Project Workflow

1. **Data Exploration & Visualization**
   - Summary statistics, distributions, and correlations
   - Pairplots, heatmaps, histograms, and boxplots to understand feature separability

2. **Data Preprocessing**
   - Splitting dataset into training and testing sets (80/20 split)
   - No missing values, so minimal cleaning required

3. **Model Training**
   - Implemented multiple algorithms:
     - Logistic Regression  
     - K-Nearest Neighbors (KNN)  
     - Decision Tree  
     - Support Vector Machine (SVM)  
     - Random Forest  

4. **Model Evaluation**
   - Accuracy scores on test data
   - Confusion matrices to analyze predictions
   - Comparison of performance across models

5. **Prediction on New Data**
   - Model can classify unseen flower measurements

---

## 🎯 Results

- **Best Models:** Random Forest  
- **Accuracy:** ~97–100% on test data  
- **Insights:**  
  - Petal length and petal width are the most influential features  
  - Iris Setosa is easily separable, while Versicolor and Virginica overlap slightly  

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - NumPy, Pandas (data handling)  
  - Matplotlib, Seaborn (visualization)  
  - Scikit-learn (machine learning models & evaluation)  

---

## 🚀 How to Run

Clone the repository:
```bash
git clone https://github.com/TalluriMahesh54/Iris_flower_classicifaction.git
cd iris-classification
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook iris_classification.ipynb
```
## 📂 Repository Structure

```
iris-classification/
│── iris_classification.ipynb   # Main notebook
│── requirements.txt            # Project dependencies
│── README.md                   # Project documentation

---

## 🏆 Learning Outcomes

* Understanding the end-to-end ML workflow
* Applying classification algorithms
* Comparing models based on performance
* Visualizing data to extract insights

This project is a great starting point for **machine learning beginners** and a solid portfolio project to showcase data science skills.

---

## 📌 Future Enhancements

* Deploy the model using **Streamlit** or **Flask**
* Hyperparameter tuning with GridSearchCV
* Export trained model with joblib for reuse

---
