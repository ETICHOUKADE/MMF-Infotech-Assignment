# Logistic Regression on Income Dataset

This project applies **Logistic Regression** to predict whether a person earns more than $50K annually using the Adult Income dataset. The project includes data preprocessing, model training, and evaluation using standard classification metrics. It includes a **Power BI segmentation dashboard** to visually analyze groups based on the dataset.
---

## Files Included

- `au_train.csv` – Training dataset  
- `au_test.csv` – Testing dataset  
- `income-Prediction Code file .ipynb` – Jupyter Notebook with full code, outputs, and analysis
- `income-Segmentation Dashboard.ipynb` – Power BI file for segmentation study  

---

## Project Workflow

### 1. Data Cleaning
- Removing duplicates  
- Handledlling missing values

### 2. Feature Encoding
- Used **Target Encoding** for categorical variables  
- Applied **One-Hot Encoding** to `race` and `sex` columns  

### 3. Feature Scaling
- Applied `StandardScaler` to standardize numerical columns

### 4. Model Training
- Trained a **Logistic Regression** model 

### 5. Model Evaluation
- Evaluated performance using:
  - **Confusion Matrix**
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1 Score**
    
---

## 🛠️ Libraries Used

- pandas  
- numpy  
- scikit-learn  
