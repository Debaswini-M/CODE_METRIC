# 🌸 Iris Flower Classification  

This project implements a **machine learning model** to classify iris flowers into species using the classic **Iris dataset**. The task involves **data preprocessing, exploratory data analysis (EDA), training a K-Nearest Neighbors (k-NN) classifier, and evaluating model performance**.  

---

## 📌 Task Description  
- **Classify iris flowers into species** using the Iris dataset.  
- Dataset contains features like sepal length, sepal width, petal length, and petal width.  

---

## 📂 Requirements  
1. Load the dataset using **Pandas** and perform exploratory data analysis.  
2. Split the dataset into **training and testing sets**.  
3. Train a **k-Nearest Neighbors (k-NN)** classifier using **Scikit-learn**.  
4. Evaluate model performance with **accuracy, F1-score, classification report, and confusion matrix**.  
5. Visualize results using **Seaborn & Matplotlib**.  

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values and zero values.
- Distribution of species in dataset.
- Pairplot visualization to show relationships between features.

---

## 🔧 Preprocessing

- Features (X): Sepal length, Sepal width, Petal length, Petal width
- Target (y): Encoded species (setosa, versicolor, virginica)
- Applied StandardScaler for feature scaling.
- Split dataset into 80% train and 20% test.

---

## 🤖 Model Training

**Model: k-Nearest Neighbors (k-NN)**

---

## 📈 Model Evaluation

Metrics used:

- Accuracy Score
- F1 Score
- Classification Report
- Confusion Matrix Visualization

---

## ✅ Results

- Accuracy: 93.33% (varies on random state)
- F1 Score: 93.26% (average='weighted')
- Confusion Matrix shows correct classification for all classes with minor misclassifications

---

## 📦 Dependencies

This project requires the following Python libraries:
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  

---

## 👩🏻‍💻 Author
 **Debaswini**

---


