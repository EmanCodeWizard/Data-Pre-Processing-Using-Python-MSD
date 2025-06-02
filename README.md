# Data-Pre-Processing-Using-Python-MSD
Here's a professional `README.md` file for your **Data Preprocessing on a Medical Student Dataset using Python** project. You can place this file in your project directory for documentation purposes.

# 🏥 Medical Student Dataset Preprocessing with Python

This project demonstrates comprehensive data preprocessing techniques on a **Medical Students Dataset** using Python. The workflow includes data cleaning, imputation, feature handling, visualization, and preparation for modeling multiple target variables such as `Diabetes` and `Smoking`.

## 📂 Dataset

The dataset (`medical_students_dataset.csv`) contains medical attributes and lifestyle information of students, including:
- Demographic data (e.g., Age, Gender, Blood Type)
- Health indicators (e.g., BMI, Blood Pressure, Cholesterol)
- Target labels: `Diabetes`, `Smoking`

## 🛠️ Libraries Used

python
pandas, numpy, matplotlib, seaborn, scikit-learn

## 📊 Data Preprocessing Steps

### 1. 📥 Load and Inspect Data

* Load dataset using `pandas`
* Drop `Student ID` as it is irrelevant to the analysis
* Separate features (`X`) and targets (`Y`)
* Split into train-test sets

### 2. 🧹 Clean and Explore

* Check for missing and duplicated data
* Remove duplicate entries
* Analyze data types and value distributions
* Visualize distributions using bar plots and histograms

### 3. 📏 Handle Missing Numerical Data

* Impute missing values in `Height`, `Weight`, and `BMI` using BMI formula
* Replace missing values in `Temperature`, `Heart Rate`, `Blood Pressure`, `Cholesterol`, and `Age` with column means

### 4. 🎲 Handle Missing Categorical Data

* Randomly impute missing values in `Gender` and `Blood Type` from existing categories

### 5. 📈 Visualization

* Compare distributions before and after imputation for both numerical and categorical columns using:

  * Histograms
  * Count plots

## 🔍 Features and Targets

* Features: Cleaned and transformed medical and demographic data
* Targets:

  * `Diabetes` (binary classification)
  * `Smoking` (binary classification)

## 📌 Results

* Visual confirmation of successful imputation
* Cleaned dataset ready for ML modeling (e.g., Logistic Regression, SVM)
* Preprocessing pipeline built using `scikit-learn`


## 📚 Future Enhancements

* Integrate full ML classification pipeline
* Export preprocessed dataset as `.csv`
* Perform feature engineering and selection
* Apply advanced imputation techniques (e.g., MICE, IterativeImputer)


## 📬 Contact

**Author: Noor ul Ieman
**Email:iemannoorul614@gmail.com
**University:** Fatima Jinnah Women's University
**Course:Data Pre Processing Using Python 

