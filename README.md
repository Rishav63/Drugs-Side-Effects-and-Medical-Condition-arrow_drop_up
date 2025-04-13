# 🧪 Drugs, Side Effects & Medical Conditions-arrow_drop_up– Data Science Project

## 🔍 Project Overview
This project focuses on exploring the relationships between drugs, their side effects, and the medical conditions they treat. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, feature engineering, and a predictive model using Random Forest to estimate drug effectiveness.

## 📁 Dataset

- **File used**: `drugs_side_effects_drugs_com.csv`
- **Rows**: 2,931  
- **Columns**: 17

### Major Columns:
- `drug_name`, `generic_name`, `brand_names`
- `drug_classes`, `medical_condition`, `side_effects`
- `rx_otc`, `pregnancy_category`, `csa`, `alcohol`
- `rating`, `no_of_reviews`, `activity`
  

## ⚙️ Tools & Libraries

| Type        | Stack                         |
|-------------|-------------------------------|
| Language    | Python                        |
| Libraries   | pandas, matplotlib, seaborn, sklearn, mlxtend, wordcloud, squarify |
| Notebook    | Jupyter                        |
| Visualization | Matplotlib, Seaborn, WordCloud |

---

## 📊 Project Steps

### 1. Data Cleaning
- Handled missing values using `fillna` and replacement strategies.
- Encoded categorical columns using `LabelEncoder`.
- Normalized numerical values using `StandardScaler`.

### 2. Exploratory Data Analysis
- Distribution plots for `ratings`
- Top conditions and drugs
- Most frequent side effects
- Heatmaps for correlations

### 3. Feature Engineering
- Created boolean flags for specific:
  - Side effects (e.g., Hives, Itching, Difficulty Breathing)
  - Drug classes (e.g., Topical steroids)
  - Medical conditions (e.g., Pain, Acne)

### 4. Visualization
- Word clouds for side effects
- Treemaps for medical condition distribution
- Bar plots for condition and class frequencies

### 5. Model Building
- Random Forest Regressor to predict `rating`
- Preprocessing: label encoding + train/test split
- Evaluation: Mean Squared Error (MSE)

## 📂 File Structure

```
📁 drugs-side-effects-analysis
├── 📄 README.md
├── 📊 EDA.ipynb
├── 🤖 model_training.ipynb
├── 📁 data
│   └── drugs_side_effects_drugs_com.csv
├── 📁 visualizations
│   ├── wordcloud.png
│   ├── treemap.png
│   └── heatmap.png
└── 📈 medical_condition_counts.csv
```

---

## 🚀 Future Improvements

- Incorporate NLP sentiment analysis from user reviews
- Create a drug recommendation system
- Deploy as a Flask or Streamlit web app
- Explore other ML models (XGBoost, SVR)

---

## 👤 Author

- **Name**: Rishav Kumar Sharma  
- **Role**: Data Analyst Intern
- **GitHub**: [github.com/rishav63](https://github.com/your-profile)  
- **Email**: rishav6363@gmail.com

