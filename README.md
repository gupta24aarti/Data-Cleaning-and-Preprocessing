# Data Cleaning & Preprocessing

This project involves the data cleaning and preprocessing steps on the Titanic dataset. The aim is to transform raw data into a suitable format for further analysis or machine learning models.

---

### 📂 Dataset

The dataset used is the famous Titanic passenger data from Kaggle:
- Includes details like passenger age, gender, ticket fare, travel class, family aboard, and survival status.

---

### Project Objectives

- Handle missing values using appropriate strategies (mean/mode imputation).
- Encode categorical variables (`Sex`, `Embarked`) into numerical values.
- Normalize numerical features for better model performance.
- Conduct basic exploratory data analysis (EDA) with visualizations.

---

### Data Cleaning Steps

- Checked for null values using `df.isnull().sum()`
- Filled missing values:
  - `Age` with **mean**
  - `Embarked` with **mode**
- Dropped unnecessary or irrelevant columns (if any)

---

### Feature Encoding

- `Sex`: Encoded as `male=1`, `female=0`
- `Embarked`: Encoded as `S=0`, `C=1`, `Q=2`

---

### Normalization

- Applied **Min-Max Scaling** 

---

### Visualizations

- Histograms for numerical features
- Boxplot for Outliers

---

### Tools Used

- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- NumPy

---

### ✅ Output

A clean, preprocessed version of the Titanic dataset ready for building predictive models like logistic regression, decision trees, etc.



