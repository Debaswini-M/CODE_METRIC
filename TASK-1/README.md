# 📩 SMS Spam Classification

## 📌 Task Overview
The goal of this task is to build a machine learning model to classify SMS messages as Spam or Not Spam.

## 📊 Dataset
- Dataset: **SMS Spam Collection Dataset**  
- Total records: **5,574 SMS messages**  
- Labels: `ham` (not spam) and `spam`  

## 🛠️ Project Workflow
1. **Data Loading & EDA**
   - Loaded dataset using `pandas`
   - Checked missing values, NA values, and dataset shape
   - Basic distribution of spam vs ham  

2. **Text Preprocessing**
   - Lowercasing text
   - Removing non-alphabetical characters
   - Removing stopwords
   - Stemming words using **PorterStemmer**  

3. **Feature Extraction**
   - Used **TF-IDF Vectorization** with `max_features=3000`  

4. **Model Training**
   Trained and tuned the following classifiers:
   - 📌 Naive Bayes (`MultinomialNB`)
   - 📌 Logistic Regression
   - 📌 Linear SVC
   - 📌 Decision Tree
   - 📌 Random Forest  

5. **Evaluation**
   - Metrics: **Accuracy, F1-score, Classification Report**
   - Plots:
     - Model comparison (Accuracy vs F1-score bar chart)
     - ROC-AUC Curves for all models
     - Confusion Matrix for the best model (SVC)  

## 📈 Results
- **Best Model:** LinearSVC  
- **Performance:**
  - Accuracy: **98.21%**
  - F1 Score: **98.19%**  

Other models (Logistic Regression, Naive Bayes) also performed very well (>97% accuracy).


### 📊 Model Performance Comparison Plot
<img width="849" height="429" alt="image" src="https://github.com/user-attachments/assets/b52d3137-7f3c-4c5a-a9e5-0142c13f65c5" />



### 🔍 ROC-AUC Curve
<img width="857" height="472" alt="image" src="https://github.com/user-attachments/assets/c6bc9803-9540-4517-a7af-9b9430bde271" />
  

### 🔲 Confusion Matrix
<img width="444" height="473" alt="image" src="https://github.com/user-attachments/assets/0198d6ba-b41c-47f6-93ae-e98bc2d3e3d6" />


---

## ⚙️ Tools & Libraries Used
- **Language:** Python 3  
- **Libraries:**  
  - `pandas`, `numpy` → Data handling  
  - `nltk` → Text preprocessing (stopwords, stemming)  
  - `scikit-learn` → ML models, TF-IDF, metrics  
  - `matplotlib` → Visualization  


---
## 👩🏻‍💻Author
`Debaswini`
---


