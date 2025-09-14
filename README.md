# Weather Prediction Project 🌦️

## 📌 Overview
This project predicts whether it will **rain tomorrow** using machine learning models.  
We applied a **full ML pipeline** including:
- Data preprocessing
- Handling missing values
- Outlier treatment
- Feature scaling
- Encoding categorical variables
- Model training and evaluation
- Visualization of results and feature importance

---

## ⚙️ Steps

### 1. Data Preprocessing
- **Missing values**:
  - Numerical columns → filled with **median**.
  - Categorical columns → filled with **mode**.
- **Outlier handling**: applied **RobustScaler**.
- **Encoding categorical data**: used **OneHotEncoder**.

### 2. Models Implemented
We tested multiple models using **Pipelines**:
- 🌳 `DecisionTreeClassifier`
- 📈 `LogisticRegression`
- ⚡ `SVC`

Each model was trained and evaluated using:
- Train/Test split
- Cross-validation

### 3. Evaluation Metrics
- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)
- **Confusion Matrix**

### 4. Visualizations
- Outliers detection (Boxplots, Histograms, % of outliers per column)
- Model performance comparison (Accuracy, CV Accuracy)
- Confusion Matrices heatmaps
- Feature Importances (Decision Tree, Logistic Regression)

---

## 📊 Results
- Models were compared based on **Accuracy** and **Cross-validation scores**.
- Decision Tree provided **feature importance insights**.
- Logistic Regression helped in identifying **linear relationships**.
- SVC achieved competitive accuracy but without direct feature importances.

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/weather-prediction.git
   cd weather-prediction
