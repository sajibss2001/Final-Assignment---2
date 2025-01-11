# Amazon Product Review Sentiment Analysis

## **Project Overview**
This project focuses on predicting the sentiment of Amazon product reviews based on textual content. The sentiment labels are binary:
- `1` for positive sentiment
- `0` for negative sentiment

---

## **Workflow**

### 1. Dataset Overview
The dataset contains the following:
- `reviewText`: Text of the product review
- `Positive`: Binary label for sentiment (1 for positive, 0 for negative)

---

### 2. Data Preprocessing
- **Handling Missing Values**: Dropped rows with missing reviews.
- **Text Preprocessing**:
  - Converted text to lowercase
  - Removed stopwords, punctuation, and numbers
  - Tokenized and lemmatized the text

---

### 3. Model Selection
The following models were chosen for sentiment classification:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

---

### 4. Model Training
- Text data was vectorized using TF-IDF.
- Models were trained on the preprocessed training data.

---

### 5. Model Evaluation
The following metrics were used:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

### 6. Hyperparameter Tuning
- Hyperparameters for the Random Forest model were optimized using GridSearchCV.

---

### 7. Comparative Analysis
The models were compared based on evaluation metrics to identify the best-performing model.

---

## **Technologies Used**
- Python
- Libraries: pandas, numpy, sklearn, nltk

---

## **Results**
- Logistic Regression: **Accuracy = X.XX**
- Random Forest: **Accuracy = Y.YY**
- SVM: **Accuracy = Z.ZZ**

---

## **How to Run**
1. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn nltk
