# Task 5: Consumer Complaint Text Classification

This project classifies consumer complaints into four categories:

0 - Credit reporting, repair, or other  
1 - Debt collection  
2 - Consumer Loan  
3 - Mortgage  

**Dataset:** [CFPB Consumer Complaint Database](https://files.consumerfinance.gov/ccdb/complaints.csv.zip)

---

## **Project Overview**

The project performs **text classification** on consumer complaints. The main steps are:

1. **Data Loading:** Download and load the dataset.  
2. **Explanatory Data Analysis (EDA):** Analyze category distribution.  
3. **Text Preprocessing:**  
   - Remove NaN complaint texts  
   - Clean text (lowercase, remove special characters, remove stopwords)  
   - Map products to category labels  
4. **Feature Engineering:** Convert text into TF-IDF features.  
5. **Model Selection:** Train multiple models:  
   - Logistic Regression  
   - Multinomial Naive Bayes  
   - Random Forest  
6. **Model Evaluation:**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion matrix  
7. **Prediction:** Use `predict_complaint()` function for new complaints.  

---

## **How to Run**

1. Open the notebook: `notebooks/kaiburr.ipynb` in [Google Colab](https://colab.research.google.com/).  
2. Install required libraries:

```bash
!pip install pandas numpy scikit-learn matplotlib seaborn nltk imbalanced-learn


### Tas5 Dataset Head Preprocessing
![Tas5 Dataset Head Preprocessing](/content/task-5/screenshots/tas5-dataset-head-preprocessing.png)

### Tas5 Dataset Model
![Tas5 Dataset Model](/content/task-5/screenshots/tas5-dataset-model.png)

### Task5 Dataset Unzip
![Task5 Dataset Unzip](/content/task-5/screenshots/task5-dataset-unzip.png)

### Task5 Model Metrics
![Task5 Model Metrics](/content/task-5/screenshots/task5-model-metrics.png)

### Task5 1
![Task5 1](/content/task-5/screenshots/task5-1.png)

### Task5 Sample Prediction
![Task5 Sample Prediction](/content/task-5/screenshots/task5-sample prediction.png)

### Task5 Cleaning
![Task5 Cleaning](/content/task-5/screenshots/task5-cleaning.png)

### Task5 SMOTE
![Task5 SMOTE](/content/task-5/screenshots/task5-smote.png)

### Task5 Confusion Matrix
![Task5 Confusion Matrix](/content/task-5/screenshots/task-5-confusion_matix.png)





