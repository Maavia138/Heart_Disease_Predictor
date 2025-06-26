# ❤️ Heart Disease Prediction

This project uses machine learning techniques to predict whether a person is at risk of heart disease based on medical attributes. The dataset used is the UCI Heart Disease Dataset. This is part of an internship task focused on applying binary classification techniques and model evaluation.

---

## 📁 Dataset

- Source : UCI Heart Disease Dataset ([Kaggle Link]((https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data?resource=download))
- Rows : Patient records
- Target Variable : `num` (converted to binary: 0 = no heart disease, 1 = heart disease)



## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn


---

## 🧪 Project Workflow

### 1. Data Cleaning
- Handled missing values using mean (numeric) and mode (categorical).
- Converted `num` column into binary `target`.

### 2. Exploratory Data Analysis (EDA)
- Distribution of heart disease in the dataset
- Correlation heatmap of features

### 3. Model Training
- Logistic Regression
- Decision Tree Classifier

### 4. Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- ROC Curve & AUC Score

### 5. Feature Importance
- Top features influencing the prediction visualized using bar charts

---

## 📊 Visualizations

The following charts are included and saved as images:
- Heart Disease Distribution
- Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Top Important Features

---

## 📌 Key Files

| File | Description |
|------|-------------|
| `heart_disease_prediction.ipynb` | Main Jupyter notebook with full analysis and model |
| `images/` | Folder containing saved plot images |
| `README.md` | Project overview |

---

## 📈 Results

- Models achieved good accuracy and AUC scores.
- Key features like **chest pain**, **maximum heart rate**, and **ST depression** were highly influential.
- Helps in early detection and prevention planning.

---

## ✅ Future Improvements

- Try more advanced models like Random Forest or XGBoost
- Hyperparameter tuning
- Deploy the model using Flask or Streamlit

---

## 🙌 Acknowledgements

- UCI Machine Learning Repository
- Scikit-learn Documentation
- Internship guidance and support

---



