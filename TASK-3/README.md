# 🍷 Wine Quality Prediction  

## 📌 Task Description    
The objective is to **create a machine learning model to predict wine quality** based on various physicochemical properties.  

---

## 📂 Dataset  
The dataset used is **WineQT.csv**, which contains physicochemical features such as acidity, chlorides, sulphates, alcohol content, etc., along with a quality score.  

- The target variable `quality` was **binarized**:  
  - `1` → Good Quality (quality >= 7)  
  - `0` → Average/Low Quality (quality < 7)  

---

## ⚙️ Requirements  
- Load and explore the dataset  
- Preprocess the data:
  - Handle missing values  
  - Drop irrelevant columns (`Id`)  
  - Normalize features using `StandardScaler`  
- Split the dataset into **training** and **testing** sets  
- Train multiple classifiers:
  - Logistic Regression  
  - Decision Tree Classifier  
  - Linear SVC  
  - Random Forest  
- Evaluate models using:
  - Accuracy  
  - F1 Score  
  - Classification Report  
  - ROC-AUC Curve  
  - Confusion Matrix  

---

## 📈 Results  

- **Model Performance Comparison**  

| Model                | Accuracy | F1 Score |
|-----------------------|----------|----------|
| Logistic Regression   | 0.80     | 0.52     |
| Decision Tree         | 0.86     | 0.57     |
| Linear SVC            | 0.79     | 0.51     |
| Random Forest         | **0.92** | **0.67** |

- **Best Model:** 🎯 Random Forest Classifier  
- **Visualizations:**  
  - Accuracy vs. F1 Score Bar Chart  
  - ROC Curves for all models  
  - Confusion Matrix (Random Forest)  

---

## 📷 Sample Outputs  

### ROC-AUC Curves  
<img width="851" height="390" alt="image" src="https://github.com/user-attachments/assets/48797c4d-64bf-4f15-9981-872783adb3bd" />


### Confusion Matrix (Random Forest)  
<img width="443" height="470" alt="image" src="https://github.com/user-attachments/assets/35e34fbe-a5e5-4822-83bb-1796b495bc3c" />


---

## 📌 Tech Stack

- Python 
- Pandas, NumPy for data handling
- Scikit-learn for ML models & preprocessing
- Matplotlib for visualization

---

## 👩🏻‍💻Author
  `Debaswini`

---

