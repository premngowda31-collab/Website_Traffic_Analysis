# 🚀 Website Traffic Analysis & Conversion Rate Prediction

## 📌 Overview
This project focuses on analyzing website user behavior and building machine learning models to predict **conversion rates** based on session-level data.

By leveraging data preprocessing, exploratory data analysis (EDA), and advanced regression models, the project aims to uncover key factors influencing user conversions and optimize decision-making for digital platforms.

---

## 🎯 Objectives
- Analyze website traffic patterns and user engagement
- Identify key factors impacting conversion rates
- Handle imbalanced data effectively
- Build and compare multiple regression models
- Evaluate model performance using robust metrics
- Develop a scalable ML pipeline for prediction

---

## 📂 Dataset Description
The dataset contains **2000 user session records** with the following features:

| Feature | Description |
|--------|------------|
| Page Views | Number of pages visited |
| Session Duration | Time spent in session |
| Bounce Rate | Probability of leaving quickly |
| Traffic Source | Source of traffic (Organic, Paid, Social, Direct, Referral) |
| Time on Page | Time spent on individual pages |
| Previous Visits | Number of prior visits |
| Conversion Rate | Target variable |

---

## ⚙️ Tech Stack
- **Language**: Python  
- **Libraries**:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - XGBoost
  - SciPy

---

## 🔍 Exploratory Data Analysis (EDA)
Key analyses performed:
- Distribution analysis of Page Views and Session Duration
- Traffic Source distribution visualization
- Correlation heatmap to identify feature relationships
- Scatter plots to analyze behavior vs conversion

### 📊 Insights
- Higher session duration tends to improve conversion probability
- Bounce rate negatively impacts conversion
- Traffic source significantly influences user behavior

---

## 🧹 Data Preprocessing
- Handled class imbalance using:
  - Oversampling
  - Undersampling
- Encoded categorical variables using Label Encoding & OneHotEncoder
- Standardized numerical features
- Checked and removed duplicates
- Verified missing values (none present)
- Applied **epsilon smoothing** to avoid target ceiling effect

---

## 🤖 Model Building
Implemented multiple regression models:

- Ridge Regression  
- Lasso Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  
- Support Vector Regressor  

---

## 🏆 Model Selection
**Random Forest Regressor** was selected as the final model due to its strong performance, robustness, and ability to handle non-linear relationships effectively.

---

## 📊 Evaluation Metrics
The models were evaluated using:

- R² Score  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)  
- Mean Absolute Percentage Error (MAPE)  
- Median Absolute Error  

---

## 🔬 Model Validation
- 5-Fold Cross Validation performed
- Learning Curve analysis to detect overfitting/underfitting
- Residual analysis for model error patterns
- Shapiro-Wilk test for residual normality

---

## 📈 Feature Importance
Top contributing features:
- Time on Page
- Session Duration
- Page Views
- Traffic Source

---

## 🧠 Machine Learning Pipeline
A complete ML pipeline was built using:

- ColumnTransformer  
- StandardScaler  
- OneHotEncoder  
- RandomForestRegressor  

This ensures reproducibility, scalability, and clean preprocessing.

---

## 📉 Key Insights
- User engagement metrics are strong predictors of conversion
- Returning users have higher conversion probability
- Traffic source optimization can significantly improve business outcomes
- Balanced datasets lead to better model performance

---

## 📦 Project Structure
```
📁 Website-Traffic-Analysis
│── 📄 Website_Traffic_Analysis.ipynb
│── 📄 Cleaned_Data.csv
│── 📄 Website_Traffic_Analysis.report.pdf
│── 📄 README.md
```

---

## ▶️ How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/website-traffic-analysis.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook
```

---

## 💡 Future Improvements
- Hyperparameter tuning (GridSearchCV / Optuna)
- Model deployment using Streamlit or Flask
- Real-time analytics dashboard
- Integration with live website traffic data
- Deep learning models for enhanced predictions

---

## 👨‍💻 Author
**Prem N Gowda**  
Aspiring Data Analyst  

---

## ⭐ If you found this project useful
Please consider giving it a ⭐ on GitHub!
